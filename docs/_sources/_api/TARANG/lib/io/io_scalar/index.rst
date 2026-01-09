TARANG.lib.io.io_scalar
=======================

.. py:module:: TARANG.lib.io.io_scalar


Functions
---------

.. autoapisummary::

   TARANG.lib.io.io_scalar.initial_scalar
   TARANG.lib.io.io_scalar.output_scalar
   TARANG.lib.io.io_scalar.output_field_scalar
   TARANG.lib.io.io_scalar.output_glob_scalar
   TARANG.lib.io.io_scalar.output_modes_scalar
   TARANG.lib.io.io_scalar.output_ekTk_scalar
   TARANG.lib.io.io_scalar.init_save_scalar
   TARANG.lib.io.io_scalar.file_save_scalar


Module Contents
---------------

.. py:function:: initial_scalar(para, U, T)

   Initialize the hydrodynamic and scalar field based on the input parameters.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param T: ScalarField object representing the scalar field.
   :type T: ScalarField

   :rtype: None


.. py:function:: output_scalar(para, t, U, T, univ)

   Output the scalar field and global quantities at a given time step.

   :param t: Current time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param T: ScalarField object representing the scalar field.
   :type T: ScalarField
   :param univ: UniversalArrays object for temporary storage and global quantities.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: output_field_scalar(para, t, U, T, univ)

   Save the hydrodynamic and scalar field data to a file.

   :param t: Current simulation time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param T: ScalarField object representing the scalar field.
   :type T: ScalarField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: output_glob_scalar(para, t, U, T, univ)

   Save global hydrodynamic and scalar quantities such as energy and dissipation to a file.

   :param t: Current simulation time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param T: ScalarField object representing the scalar field.
   :type T: ScalarField
   :param univ: UniversalArrays object for temporary storage and global quantities.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: output_modes_scalar(para, t, U, T, univ)

   Save specific modes of the hydrodynamic and scalar field to a file.

   :param t: Current simulation time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param T: ScalarField object representing the scalar field.
   :type T: ScalarField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: output_ekTk_scalar(para, t, U, T, univ)

   Save the energy and transfer spectra of the hydrodynamic and scalar field to a file.

   :param t: Current simulation time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param T: ScalarField object representing the scalar field.
   :type T: ScalarField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: init_save_scalar(para, U, T)

   Initialize files for saving energy and transfer spectra, global hydrodynamic quantities,
   field save times, time steps, and specific modes of the hydrodynamic field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param T: ScalarField object representing the scalar field.
   :type T: ScalarField

   :rtype: None


.. py:function:: file_save_scalar(para, U, T, univ)

   Save the energy and transfer spectra, global hydrodynamic quantities, field save times,
   time steps, and specific modes of the hydrodynamic field to their respective files.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param T: ScalarField object representing the scalar field.
   :type T: ScalarField
   :param univ: UniversalArrays object for temporary storage and global quantities.
   :type univ: UniversalArrays

   :rtype: None


