TARANG.lib.solver_fns.compute_nlin_mhd
======================================

.. py:module:: TARANG.lib.solver_fns.compute_nlin_mhd


Functions
---------

.. autoapisummary::

   TARANG.lib.solver_fns.compute_nlin_mhd.compute_prod_transform
   TARANG.lib.solver_fns.compute_nlin_mhd.compute_nlin_mhd
   TARANG.lib.solver_fns.compute_nlin_mhd.UB_to_Elsasser
   TARANG.lib.solver_fns.compute_nlin_mhd.Elsasser_to_UB
   TARANG.lib.solver_fns.compute_nlin_mhd.Elsasser_to_UB_nlin
   TARANG.lib.solver_fns.compute_nlin_mhd.compute_cross_helicity
   TARANG.lib.solver_fns.compute_nlin_mhd.Elsasser_to_UB_force
   TARANG.lib.solver_fns.compute_nlin_mhd.compute_dt_mhd
   TARANG.lib.solver_fns.compute_nlin_mhd.UB_to_Elsasser_real
   TARANG.lib.solver_fns.compute_nlin_mhd.Elsasser_to_UB_real


Module Contents
---------------

.. py:function:: compute_prod_transform(para, U, B, univ)

   Compute the product and transform for the magnetohydrodynamic (MHD) field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: compute_nlin_mhd(para, t, U, B, univ)

   Compute the nonlinear terms for the magnetohydrodynamic (MHD) field.

   :param t: Current time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: UB_to_Elsasser(para, U, B, univ)

   Convert velocity and magnetic fields to Elsasser variables.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: Elsasser_to_UB(para, U, B, univ)

   Convert Elsasser variables back to velocity and magnetic fields.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: Elsasser_to_UB_nlin(para, U, B, univ)

   Convert nonlinear terms of Elsasser variables back to velocity and magnetic fields.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: compute_cross_helicity(para, U, B)

   Compute the cross helicity of the velocity and magnetic fields.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField

   :returns: Cross helicity of the velocity and magnetic fields.
   :rtype: float


.. py:function:: Elsasser_to_UB_force(para, U, B, univ)

   Convert forcing terms of Elsasser variables back to velocity and magnetic fields.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: compute_dt_mhd(para, U, B, univ)

   Compute the time step for the magnetohydrodynamic (MHD) field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: UB_to_Elsasser_real(para, U, B, univ)

.. py:function:: Elsasser_to_UB_real(para, U, B, univ)

