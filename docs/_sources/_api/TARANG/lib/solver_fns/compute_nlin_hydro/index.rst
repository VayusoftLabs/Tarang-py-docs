TARANG.lib.solver_fns.compute_nlin_hydro
========================================

.. py:module:: TARANG.lib.solver_fns.compute_nlin_hydro


Functions
---------

.. autoapisummary::

   TARANG.lib.solver_fns.compute_nlin_hydro.compute_prod_transform
   TARANG.lib.solver_fns.compute_nlin_hydro.compute_nlin_omega
   TARANG.lib.solver_fns.compute_nlin_hydro.compute_nlin_hydro
   TARANG.lib.solver_fns.compute_nlin_hydro.compute_dt_hydro


Module Contents
---------------

.. py:function:: compute_prod_transform(para, U, univ)

   Compute the product and transform for the hydrodynamic field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
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


.. py:function:: compute_nlin_hydro(para, t, U, univ)

   Compute the nonlinear terms for the hydrodynamic field.

   :param t: Current time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
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


