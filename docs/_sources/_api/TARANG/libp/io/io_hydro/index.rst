TARANG.libp.io.io_hydro
=======================

.. py:module:: TARANG.libp.io.io_hydro


Attributes
----------

.. autoapisummary::

   TARANG.libp.io.io_hydro.comm
   TARANG.libp.io.io_hydro.rank
   TARANG.libp.io.io_hydro.nprocs


Functions
---------

.. autoapisummary::

   TARANG.libp.io.io_hydro.initial_hydro
   TARANG.libp.io.io_hydro.output_hydro
   TARANG.libp.io.io_hydro.output_field_hydro
   TARANG.libp.io.io_hydro.output_glob_hydro
   TARANG.libp.io.io_hydro.output_modes_hydro
   TARANG.libp.io.io_hydro.output_ekTk_hydro
   TARANG.libp.io.io_hydro.init_save_hydro
   TARANG.libp.io.io_hydro.file_save_hydro


Module Contents
---------------

.. py:data:: comm

.. py:data:: rank

.. py:data:: nprocs

.. py:function:: initial_hydro(U, univ)

   Initialize the hydrodynamic field based on the input parameters.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: output_hydro(t, U, univ)

   Output the hydrodynamic field and global quantities at a given time step.

   :param t: Current simulation time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param univ: UniversalArrays object for temporary storage and global quantities.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: output_field_hydro(t, U, univ)

   Save the hydrodynamic field data to a file.

   :param t: Current simulation time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: output_glob_hydro(t, U, univ)

   Save global hydrodynamic quantities such as energy and dissipation to a file.

   :param t: Current simulation time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param univ: UniversalArrays object for temporary storage and global quantities.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: output_modes_hydro(t, U, univ)

   Save specific modes of the hydrodynamic field to a file.

   :param t: Current simulation time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: output_ekTk_hydro(t, U, univ)

   Save the energy and transfer spectra of the hydrodynamic field to a file.

   :param t: Current simulation time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: init_save_hydro(U)

   Initialize files for saving energy and transfer spectra, global hydrodynamic quantities,
   field save times, time steps, and specific modes of the hydrodynamic field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField

   :rtype: None


.. py:function:: file_save_hydro(U, univ)

   Save the energy and transfer spectra, global hydrodynamic quantities, field save times,
   time steps, and specific modes of the hydrodynamic field to their respective files.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param univ: UniversalArrays object for temporary storage and global quantities.
   :type univ: UniversalArrays

   :rtype: None


