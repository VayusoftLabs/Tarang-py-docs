TARANG.lib.fields.scalar_field
==============================

.. py:module:: TARANG.lib.fields.scalar_field


Classes
-------

.. autoapisummary::

   TARANG.lib.fields.scalar_field.ScalarField


Module Contents
---------------

.. py:class:: ScalarField(para)

   Class representing a scalar field for the TARANG solver.

   .. attribute:: fk

      Array for the Fourier components of the scalar field.

      :type: array-like

   .. attribute:: f

      Array for the real-space components of the scalar field.

      :type: array-like

   .. attribute:: nlin

      Array for the nonlinear components of the scalar field.

      :type: array-like

   .. attribute:: force_f

      Array for the forcing components of the scalar field.

      :type: array-like

   .. attribute:: tot_energy

      Array for the total energy.

      :type: array-like

   .. attribute:: ek

      Array for the energy spectrum.

      :type: array-like

   .. attribute:: Tk

      Array for the transfer function.

      :type: array-like

   .. attribute:: ek_table

      Table for the energy spectrum.

      :type: array-like

   .. attribute:: Tk_table

      Table for the transfer function.

      :type: array-like

   .. attribute:: total_energy

      Array for total energy.

      :type: array-like

   .. attribute:: total_dissipation

      Array for total dissipation.

      :type: array-like

   .. attribute:: standard_dissipation

      Array for standard dissipation.

      :type: array-like

   .. attribute:: hypo_dissipation

      Array for hypo dissipation (if enabled).

      :type: array-like

   .. attribute:: hyper_dissipation

      Array for hyper dissipation (if enabled).

      :type: array-like

   .. attribute:: Tk_modes_t

      Array for the time evolution of the transfer function.

      :type: array-like

   .. attribute:: Tk_mode

      Array for the transfer function.

      :type: array-like


   .. py:attribute:: para


   .. py:attribute:: fk
      :value: []



   .. py:attribute:: f
      :value: []



   .. py:attribute:: nlin
      :value: []



   .. py:attribute:: force_f
      :value: []



   .. py:attribute:: tot_energy
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



   .. py:attribute:: Tk_modes_t
      :value: []



   .. py:attribute:: Tk_mode
      :value: []



   .. py:method:: set_arrays()

      Set the arrays for the scalar field based on the simulation parameters.



   .. py:method:: init_cond(fk)

      Initialize the scalar field with given Fourier components.

      :param fk: Array for the Fourier components of the scalar field.
      :type fk: array-like



   .. py:method:: init_cond_real(f)

      Initialize the scalar field with given Real components.

      :param f: Array for the Real components of the scalar field.
      :type f: array-like



   .. py:method:: compute_total_energy()

      Compute the total energy of the scalar field.

      :returns: Total energy of the scalar field.
      :rtype: float



   .. py:method:: compute_dissipation()

      Compute the dissipation of the scalar field.

      :returns: Dissipation of the scalar field.
      :rtype: float



   .. py:method:: compute_dissipation_alter(power)

      Compute the alternative dissipation of the scalar field.

      :param power: Power to which the wavenumber is raised.
      :type power: int

      :returns: Alternative dissipation of the scalar field.
      :rtype: float



   .. py:method:: compute_ekTk(univ)

      Compute the energy spectrum and transfer function.

      :param univ: UniversalArrays object for temporary storage.
      :type univ: UniversalArrays, optional



   .. py:method:: T_to_Tcopy(univ)

      Copy the scalar field to the universal arrays.

      :param univ: UniversalArrays object for temporary storage.
      :type univ: UniversalArrays, optional



   .. py:method:: Tcopy_to_T(univ)

      Copy the universal arrays to the scalar field.

      :param univ: UniversalArrays object for temporary storage.
      :type univ: UniversalArrays, optional



