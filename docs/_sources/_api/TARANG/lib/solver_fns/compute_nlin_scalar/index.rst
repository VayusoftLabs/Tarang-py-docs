TARANG.lib.solver_fns.compute_nlin_scalar
=========================================

.. py:module:: TARANG.lib.solver_fns.compute_nlin_scalar


Functions
---------

.. autoapisummary::

   TARANG.lib.solver_fns.compute_nlin_scalar.compute_prod_transform
   TARANG.lib.solver_fns.compute_nlin_scalar.compute_nlin_omega
   TARANG.lib.solver_fns.compute_nlin_scalar.compute_nlin_scalar
   TARANG.lib.solver_fns.compute_nlin_scalar.compute_dt_hydro


Module Contents
---------------

.. py:function:: compute_prod_transform(para, U, T, univ)

   Compute the product and transform for the scalar field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param T: ScalarField object representing the scalar field.
   :type T: ScalarField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: compute_nlin_omega(para, U, univ)

   Compute the nonlinear terms for the vorticity field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: compute_nlin_scalar(para, t, U, T, univ)

   Compute the nonlinear terms for the scalar field.

   :param t: Current time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param T: ScalarField object representing the scalar field.
   :type T: ScalarField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: compute_dt_hydro(para, U, univ)

   Compute the time step for the hydrodynamic field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


