# Defining Initial Conditions

To specify a custom initial condition case, set the following parameters in `para.py` according to your requirements or preferences. The `INPUT_SET_CASE = True` flag is required for any case where input is defined through the code rather than provided by the user via a field file.

## Predefined Field Configurations

Use a built-in initialization method by setting the input case in `para.py`:

```python
INPUT_SET_CASE = True
input_case = 'taylor-green'
```

## User-Defined Fields

Define custom initial conditions by specifying `'custom'` as the input case:

```python
INPUT_SET_CASE = True
input_case = 'custom'
```

The initial condition can be specified in three different ways: through Fourier modes, a real-space field, or directly from a field dataset.

### Fourier Modes

For each solver, initial conditions can be provided through Fourier modes. For example, with the Hydrodynamic solver, modes and their respective amplitudes can be defined in the `init_modes/init_hydro.py` file.

Modes can be assigned as follows:

```python
# Assigning amplitudes to specific Fourier modes
Vkx[1,0] = 0+0j  # Mode (1,0) has zero amplitude in the x-direction
Vkz[1,0] = 1+0j  # Mode (1,0) has amplitude 1 in the z-direction

Vkx[0,1] = 1+0j
Vkz[0,1] = 0+0j

Vkx[1,1] = 0-1j
Vkz[1,1] = 0+1j

Vkx[-1,0] = 0+0j
Vkz[-1,0] = 1+0j
```

Here:

- `Vkx` and `Vkz` correspond to components of the velocity field.
- The indices specify the Fourier modes to which the amplitude is assigned.
- The same approach can be applied to the magnetic field in the Magnetohydrodynamics solver and the scalar field in the Scalar solver.
- The last index always denotes the mode activated in the Z-direction, which is always positive.

### Real-Space Initialization

Alternatively, initial conditions can be provided in real space and then transformed into Fourier modes for compatibility with the spectral solver.

A real-space field can be defined as follows:

```python
X, Z = ncp.meshgrid(ncp.arange(Nx), ncp.arange(Nz))

Vx = ncp.cos(X) * ncp.sin(Z)
Vz = ncp.sin(X) * ncp.cos(Z)

Vkx = forward_transform(Vx, Vkx)
Vkz = forward_transform(Vz, Vkz)
```

- `ncp` refers to either NumPy or CuPy, depending on the computation device (CPU or GPU).
- The `forward_transform` function applies a Fourier transform to convert real-space data into spectral space.

## HDF5 Dataset Input

Initial conditions can also be provided via `.h5` datasets by specifying the path in `para.py`:

```python
INPUT_SET_CASE = False

INPUT_FROM_FILE = True
INPUT_REAL_FIELD = False  # Set to True if the field is in real space

input_file_name = 'init_cond.h5'
input_dir = 'path/to/directory/'
```

This method allows reusing a previously generated field as input for a new simulation run by simply providing the path and file name.

- The datasets for each field can be named in the `paraIO.py` file.
- Fourier fields have dimensions `[Nx, Ny, Nz//2+1]` for 3D and `[Nx, Nz//2+1]` for 2D.
- Real fields have dimensions `[Nx, Ny, Nz]` for 3D and `[Nx, Nz]` for 2D.
- When `INPUT_REAL_FIELD = False`, the `.h5` dataset should contain Fourier-space data.
- If `INPUT_REAL_FIELD = True`, the dataset should store real-space field values, which will be transformed internally.

Each method provides flexible initialization options for different solvers, depending on computational requirements and problem setup.