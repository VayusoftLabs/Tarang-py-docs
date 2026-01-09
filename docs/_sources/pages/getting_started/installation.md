# Installation

## Sequential Solver

Please ensure the following required packages are installed with Python 3.10 or higher for optimal performance:

- `numpy`
- `pyFFTW` (for CPU-based FFT)
- `cupy` (for GPU support)
- `h5py`

Make sure `cupy` is installed for the available cuda version. For example,

```bash
pip3 install numpy pyFFTW h5py cupy-cuda12x
```

## Parallel solver

To utilize the **parallel solver**, ensure all dependencies are installed.

### MPI4PY Installation

For `mpi4py`, ensure **CUDA-aware OpenMPI** is installed. Then run:

```bash
CC=mpicc pip install mpi4py
```

### Parallel HDF5 Installation

Download and build **Parallel HDF5** from the [HDF5 official site](https://www.hdfgroup.org/downloads/hdf5/source-code/):

```bash
./configure --enable-parallel --enable-shared --prefix=<installation_path>
make
make check
make install
```

### h5py with MPI Support

To install `h5py` with MPI support:

```bash
CC='mpicc' HDF5_MPI='ON' HDF5_DIR=<installation_path> pip install --no-binary=h5py h5py
```

### FFT setup

To build the bindings for FFT make sure the package `pybind11` is installed and add the path to **CUDA-aware OpenMPI** where specified with the placeholders:

```bash
CPLUS_INCLUDE_PATH=<installation_path>/include nvcc -shared -std=c++14 -Xcompiler -fPIC $(python3 -m pybind11 --includes) start.cu -o my_fft$(python3-config --extension-suffix) -L <installation_path>/lib -lmpi -lcufft -Xptxas -O3 --disable-warnings
```
