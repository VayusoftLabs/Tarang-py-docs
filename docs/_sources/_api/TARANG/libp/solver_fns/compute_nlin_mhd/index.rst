TARANG.libp.solver_fns.compute_nlin_mhd
=======================================

.. py:module:: TARANG.libp.solver_fns.compute_nlin_mhd


Attributes
----------

.. autoapisummary::

   TARANG.libp.solver_fns.compute_nlin_mhd.comm
   TARANG.libp.solver_fns.compute_nlin_mhd.rank
   TARANG.libp.solver_fns.compute_nlin_mhd.nprocs


Functions
---------

.. autoapisummary::

   TARANG.libp.solver_fns.compute_nlin_mhd.compute_nlin_mhd
   TARANG.libp.solver_fns.compute_nlin_mhd.UB_to_Elsasser
   TARANG.libp.solver_fns.compute_nlin_mhd.Elsasser_to_UB
   TARANG.libp.solver_fns.compute_nlin_mhd.Elsasser_to_UB_nlin
   TARANG.libp.solver_fns.compute_nlin_mhd.compute_cross_helicity
   TARANG.libp.solver_fns.compute_nlin_mhd.Elsasser_to_UB_force
   TARANG.libp.solver_fns.compute_nlin_mhd.compute_dt_mhd


Module Contents
---------------

.. py:data:: comm

.. py:data:: rank

.. py:data:: nprocs

.. py:function:: compute_nlin_mhd(t, U, W, univ)

.. py:function:: UB_to_Elsasser(U, W, univ)

.. py:function:: Elsasser_to_UB(U, W, univ)

.. py:function:: Elsasser_to_UB_nlin(U, W, univ)

.. py:function:: compute_cross_helicity(U, W)

.. py:function:: Elsasser_to_UB_force(U, W, univ)

.. py:function:: compute_dt_mhd(U, W, univ)

