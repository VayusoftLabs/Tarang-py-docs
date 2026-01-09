
Welcome to Tarang's documentation!
==================================

**Tarang** is a pseudo-spectral solver designed for Hydrodynamic Turbulence. It leverages object-oriented programming and high-performance libraries like **NumPy** and **CuPy** for efficient computations, supporting both CPU and GPU environments. Equipped with a **Graphical User Interface (GUI)** and robust **post-processing** capabilities, Tarang simplifies running simulations and analyzing data, making it an ideal tool for studying turbulence.

Tarang can solve a variety of **Partial Differential Equations (PDEs)** in turbulent flows across both 2D and 3D domains:

* **Hydrodynamics**
* **Magnetohydrodynamics (MHD)**
* **Rayleigh-Bénard Convection**
* **Scalar field**

Additionally, Tarang supports various external forcing mechanisms including random modal forcing, bulk rotation and buoyancy.

The post-processing suite allows users to extract and analyze key simulation results using key quantities such as energy, dissipation, energy spectra, and flux for the fields involved.

.. toctree::
   :caption: Getting Started
   :maxdepth: 2

   pages/getting_started/installation

   pages/getting_started/usage

   pages/getting_started/initconds

.. toctree::
   :caption: Test Cases
   :maxdepth: 1

   pages/test_cases/3d_hydro
   pages/test_cases/2d_hydro
   .. pages/test_cases/3d_scalar
   .. pages/test_cases/2d_scalar
   .. pages/test_cases/3d_mhd
   .. pages/test_cases/2d_mhd

.. toctree::
   :caption: Reference
   :hidden:

   _api/index

   modindex
   genindex


