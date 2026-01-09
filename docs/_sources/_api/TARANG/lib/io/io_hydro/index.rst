TARANG.lib.io.io_hydro
======================

.. py:module:: TARANG.lib.io.io_hydro


Functions
---------

.. autoapisummary::

   TARANG.lib.io.io_hydro.initial_hydro
   TARANG.lib.io.io_hydro.output_hydro
   TARANG.lib.io.io_hydro.output_field_hydro
   TARANG.lib.io.io_hydro.output_glob_hydro
   TARANG.lib.io.io_hydro.output_modes_hydro
   TARANG.lib.io.io_hydro.output_ekTk_hydro
   TARANG.lib.io.io_hydro.init_save_hydro
   TARANG.lib.io.io_hydro.file_save_hydro


Module Contents
---------------

.. py:function:: initial_hydro(para, U)

   Initialize the hydrodynamic field based on the input parameters.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField

   :rtype: None


.. py:function:: output_hydro(para, t, U, univ)

   Output the hydrodynamic field and global quantities at a given time step.

   :param t: Current simulation time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param univ: UniversalArrays object for temporary storage and global quantities.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: output_field_hydro(para, t, U, univ)

   Save the hydrodynamic field data to a file.

   :param t: Current simulation time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: output_glob_hydro(para, t, U, univ)

   Save global hydrodynamic quantities such as energy and dissipation to a file.

   :param t: Current simulation time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param univ: UniversalArrays object for temporary storage and global quantities.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: output_modes_hydro(para, t, U, univ)

   Save specific modes of the hydrodynamic field to a file.

   :param t: Current simulation time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: output_ekTk_hydro(para, t, U, univ)

   Save the energy and transfer spectra of the hydrodynamic field to a file.

   :param t: Current simulation time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: init_save_hydro(para, U)

   Initialize files for saving energy and transfer spectra, global hydrodynamic quantities,
   field save times, time steps, and specific modes of the hydrodynamic field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField

   :rtype: None


.. py:function:: file_save_hydro(para, U, univ)

   Save the energy and transfer spectra, global hydrodynamic quantities, field save times,
   time steps, and specific modes of the hydrodynamic field to their respective files.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param univ: UniversalArrays object for temporary storage and global quantities.
   :type univ: UniversalArrays

   :rtype: None


