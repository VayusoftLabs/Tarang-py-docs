TARANG.libp.solver_fns.compute_nlin_hydro
=========================================

.. py:module:: TARANG.libp.solver_fns.compute_nlin_hydro


Attributes
----------

.. autoapisummary::

   TARANG.libp.solver_fns.compute_nlin_hydro.comm
   TARANG.libp.solver_fns.compute_nlin_hydro.rank
   TARANG.libp.solver_fns.compute_nlin_hydro.nprocs


Functions
---------

.. autoapisummary::

   TARANG.libp.solver_fns.compute_nlin_hydro.compute_prod_transform
   TARANG.libp.solver_fns.compute_nlin_hydro.compute_nlin_hydro
   TARANG.libp.solver_fns.compute_nlin_hydro.compute_dt_hydro


Module Contents
---------------

.. py:data:: comm

.. py:data:: rank

.. py:data:: nprocs

.. py:function:: compute_prod_transform(U, univ)

   Compute the product and transform for the hydrodynamic field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: compute_nlin_hydro(t, U, univ)

   Compute the nonlinear terms for the hydrodynamic field.

   :param t: Current time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: compute_dt_hydro(U, univ)

