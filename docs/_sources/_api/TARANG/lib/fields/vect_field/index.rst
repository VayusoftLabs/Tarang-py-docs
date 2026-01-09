TARANG.lib.fields.vect_field
============================

.. py:module:: TARANG.lib.fields.vect_field


Classes
-------

.. autoapisummary::

   TARANG.lib.fields.vect_field.VectorField


Module Contents
---------------

.. py:class:: VectorField(para)

   Class representing a vector field for the TARANG solver.

   .. attribute:: Vkx

      Arrays for the Fourier components of the vector field in the x direction.

      :type: array-like

   .. attribute:: Vky

      Arrays for the Fourier components of the vector field in the y direction.

      :type: array-like

   .. attribute:: Vkz

      Arrays for the Fourier components of the vector field in the z direction.

      :type: array-like

   .. attribute:: Vx

      Arrays for the real-space components of the vector field in the x direction.

      :type: array-like

   .. attribute:: Vy

      Arrays for the real-space components of the vector field in the y direction.

      :type: array-like

   .. attribute:: Vz

      Arrays for the real-space components of the vector field in the z direction.

      :type: array-like

   .. attribute:: force_Vx

      Arrays for the forcing components of the vector field in the x direction.

      :type: array-like

   .. attribute:: force_Vy

      Arrays for the forcing components of the vector field in the y direction.

      :type: array-like

   .. attribute:: force_Vz

      Arrays for the forcing components of the vector field in the z direction.

      :type: array-like

   .. attribute:: nlinx

      Arrays for the nonlinear components of the vector field in the x direction.

      :type: array-like

   .. attribute:: nliny

      Arrays for the nonlinear components of the vector field in the y direction.

      :type: array-like

   .. attribute:: nlinz

      Arrays for the nonlinear components of the vector field in the z direction.

      :type: array-like

   .. attribute:: ek

      Arrays for the energy spectra.

      :type: array-like

   .. attribute:: Tk

      Arrays for the transfer spectra.

      :type: array-like

   .. attribute:: ek_table

      Tables for the energy spectra.

      :type: array-like

   .. attribute:: Tk_table

      Tables for the transfer spectra.

      :type: array-like

   .. attribute:: total_energy

      Arrays for total energy.

      :type: array-like

   .. attribute:: total_dissipation

      Arrays for total dissipation.

      :type: array-like

   .. attribute:: standard_dissipation

      Arrays for standard dissipation.

      :type: array-like

   .. attribute:: hypo_dissipation

      Arrays for hypo dissipation (if enabled).

      :type: array-like

   .. attribute:: hyper_dissipation

      Arrays for hyper dissipation (if enabled).

      :type: array-like

   .. attribute:: divergence

      Array for the divergence of the vector field.

      :type: array-like

   .. attribute:: total_injection

      Array for the total energy injection.

      :type: array-like

   .. attribute:: ur

      Array for the velocity components.

      :type: array-like

   .. attribute:: Vkx_modes_t

      Arrays for the time evolution of the Fourier modes in the x direction.

      :type: array-like

   .. attribute:: Vky_modes_t

      Arrays for the time evolution of the Fourier modes in the y direction.

      :type: array-like

   .. attribute:: Vkz_modes_t

      Arrays for the time evolution of the Fourier modes in the z direction.

      :type: array-like

   .. attribute:: Vkx_mode

      Arrays for the Fourier modes in the x direction.

      :type: array-like

   .. attribute:: Vky_mode

      Arrays for the Fourier modes in the y direction.

      :type: array-like

   .. attribute:: Vkz_mode

      Arrays for the Fourier modes in the z direction.

      :type: array-like


   .. py:attribute:: para


   .. py:attribute:: Vkx
      :value: []



   .. py:attribute:: Vky
      :value: []



   .. py:attribute:: Vkz
      :value: []



   .. py:attribute:: Vx
      :value: []



   .. py:attribute:: Vy
      :value: []



   .. py:attribute:: Vz
      :value: []



   .. py:attribute:: force_Vx
      :value: []



   .. py:attribute:: force_Vy
      :value: []



   .. py:attribute:: force_Vz
      :value: []



   .. py:attribute:: nlinx
      :value: []



   .. py:attribute:: nliny
      :value: []



   .. py:attribute:: nlinz
      :value: []



   .. py:attribute:: ek
      :value: []



   .. py:attribute:: Tk
      :value: []



   .. py:attribute:: ek_table
      :value: []



   .. py:attribute:: Tk_table
      :value: []



   .. py:attribute:: total_energy
      :value: []



   .. py:attribute:: total_dissipation
      :value: []



   .. py:attribute:: standard_dissipation
      :value: []



   .. py:attribute:: divergence
      :value: []



   .. py:attribute:: total_injection
      :value: []



   .. py:attribute:: ur
      :value: []



   .. py:attribute:: Vkx_modes_t
      :value: []



   .. py:attribute:: Vky_modes_t
      :value: []



   .. py:attribute:: Vkz_modes_t
      :value: []



   .. py:attribute:: Vkx_mode
      :value: []



   .. py:attribute:: Vkz_mode
      :value: []



   .. py:attribute:: Vky_mode
      :value: []



   .. py:method:: set_arrays()

      Set the arrays for the vector field based on the simulation parameters.



   .. py:method:: init_cond(Vkx, Vky, Vkz)

      Initialize the vector field with given Fourier components.

      :param Vkx: Arrays for the Fourier components of the vector field in the x direction.
      :type Vkx: array-like
      :param Vky: Arrays for the Fourier components of the vector field in the y direction.
      :type Vky: array-like
      :param Vkz: Arrays for the Fourier components of the vector field in the z direction.
      :type Vkz: array-like



   .. py:method:: init_cond_real(Vx, Vy, Vz)

      Initialize the vector field with given Real components.

      :param Vx: Arrays for the Real components of the vector field in the x direction.
      :type Vx: array-like
      :param Vy: Arrays for the Real components of the vector field in the y direction.
      :type Vy: array-like
      :param Vz: Arrays for the Real components of the vector field in the z direction.
      :type Vz: array-like



   .. py:method:: compute_omega()

      Initialize the derived field with the vorticity components from the velocity field.



   .. py:method:: compute_vecpot()

      Initialize the derived field with the vector potential components from the magnetic field.



   .. py:method:: update2D_Vkz(kx, kz)

      Update the Vkz component for 2D simulations.

      :param kx: Wavenumber in the x direction.
      :type kx: int
      :param kz: Wavenumber in the z direction.
      :type kz: int



   .. py:method:: update3D_Vkz(kx, ky, kz)

      Update the Vkz component for 3D simulations.

      :param kx: Wavenumber in the x direction.
      :type kx: int
      :param ky: Wavenumber in the y direction.
      :type ky: int
      :param kz: Wavenumber in the z direction.
      :type kz: int



   .. py:method:: compute_divergence()

      Compute the divergence of the vector field.

      :returns: Maximum absolute value of the divergence.
      :rtype: float



   .. py:method:: compute_total_energy()

      Compute the total energy of the vector field.

      :returns: Total energy of the vector field.
      :rtype: float



   .. py:method:: compute_total_energy_w()

      Compute the total energy of the vector field.

      :returns: Total energy of the vector field.
      :rtype: float



   .. py:method:: compute_total_injection()

      Compute the total energy injection of the vector field.

      :returns: Total energy injection of the vector field.
      :rtype: float



   .. py:method:: compute_dissipation()

      Compute the dissipation of the vector field.

      :returns: Dissipation of the vector field.
      :rtype: float



   .. py:method:: compute_dissipation_alter(power)

      Compute the alternative dissipation of the vector field.

      :param power: Power to which the wavenumber is raised.
      :type power: int

      :returns: Alternative dissipation of the vector field.
      :rtype: float



   .. py:method:: compute_ekTk(univ)

      Compute the energy spectrum and transfer function.

      :param univ: UniversalArrays object for temporary storage.
      :type univ: UniversalArrays, optional



   .. py:method:: compute_ekTk_w(univ)

      Compute the energy spectrum and transfer function.

      :param univ: UniversalArrays object for temporary storage.
      :type univ: UniversalArrays, optional



   .. py:method:: U_to_Ucopy(univ)

      Copy the vector field to the universal arrays.

      :param univ: UniversalArrays object for temporary storage.
      :type univ: UniversalArrays, optional



   .. py:method:: Ucopy_to_U(univ)

      Copy the universal arrays to the vector field.

      :param univ: UniversalArrays object for temporary storage.
      :type univ: UniversalArrays, optional



   .. py:method:: B_to_Bcopy(univ)

      Copy the magnetic field to the universal arrays.

      :param univ: UniversalArrays object for temporary storage.
      :type univ: UniversalArrays, optional



   .. py:method:: Bcopy_to_B(univ)

      Copy the universal arrays to the magnetic field.

      :param univ: UniversalArrays object for temporary storage.
      :type univ: UniversalArrays, optional



