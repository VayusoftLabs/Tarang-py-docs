# Usage

## Sequential Solver

Before running the code, configure `para.py` to match your requirements and provide an initial `.h5` file with the necessary field data. If needed, edit `paraIO.py` to modify dataset names. You can then execute the solver via CLI or GUI.

Or, directly run the bundled executable.

**Note:** Do not remove any variables from the `para.py` or `paraIO.py` files. Replace `python3` with `python` as required.

```bash
python3 tarang_cli.py
```

## Parallel Solver

After setup, execute the parallel solver using `mpiexec` by specifying the number of processes:

```bash
mpiexec -n <num_processes> python3 tarang_cli.py -n <num_processes>
```

Run with `CUDA_VISIBLE_DEVICES` if you wish to use specific GPUs:

```bash
CUDA_VISIBLE_DEVICES=1,2 mpiexec -n <num_processes> python3 tarang_cli.py
```

## Validator

After making changes to the code, validate the output using the built-in validator. This tool compares new results with previously confirmed data. Use the following command template to validate:

```bash
python3 tarang_cli.py validate <kind> <dim> <nx> <ny> <nz> <scheme> dt=<bool> <device>
```

Replace the placeholders:

- `<kind>`: Type of simulation (e.g., HYDRO, MHD, SCALAR, or RBC)
- `<dim>`: Dimensions (2D or 3D)
- `<nx> <ny> <nz>`: Grid resolutions
- `<scheme>`: Numerical scheme (EULER/RK2/RK4)
- `dt=<bool>`: Time stepping flag (true/false)
- `<device>`: Which device runs the code (GPU/CPU)
