TARANG.lib.io.io_mhd
====================

.. py:module:: TARANG.lib.io.io_mhd


Functions
---------

.. autoapisummary::

   TARANG.lib.io.io_mhd.initial_mhd
   TARANG.lib.io.io_mhd.output_mhd
   TARANG.lib.io.io_mhd.output_field_mhd
   TARANG.lib.io.io_mhd.output_glob_mhd
   TARANG.lib.io.io_mhd.output_modes_mhd
   TARANG.lib.io.io_mhd.output_ekTk_mhd
   TARANG.lib.io.io_mhd.init_save_mhd
   TARANG.lib.io.io_mhd.file_save_mhd


Module Contents
---------------

.. py:function:: initial_mhd(para, U, B)

   Initialize the magnetohydrodynamic (MHD) field based on the input parameters.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField

   :rtype: None


.. py:function:: output_mhd(para, t, U, B, univ)

   Output the MHD field and global quantities.

   :param t: Current time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: output_field_mhd(para, t, U, B, univ)

   Output the MHD field.

   :param t: Current time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: output_glob_mhd(para, t, U, B, univ)

   Output the global MHD quantities.

   :param t: Current time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: output_modes_mhd(para, t, U, B, univ)

   Output the modes of the MHD field.

   :param t: Current time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: output_ekTk_mhd(para, t, U, B, univ)

   Output the energy and transfer spectra of the MHD field.

   :param t: Current time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: init_save_mhd(para, U, B)

   Initialize files for saving energy and transfer spectra, global hydrodynamic quantities,
   field save times, time steps, and specific modes of the hydrodynamic field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField

   :rtype: None


.. py:function:: file_save_mhd(para, U, B, univ)

   Save the energy and transfer spectra, global magnetohydrodynamic quantities, field save times,
   time steps, and specific modes of the magnetohydrodynamic field to their respective files.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField
   :param univ: UniversalArrays object for temporary storage and global quantities.
   :type univ: UniversalArrays

   :rtype: None


