TARANG.lib.time_advance.time_advance_chaos
==========================================

.. py:module:: TARANG.lib.time_advance.time_advance_chaos


Attributes
----------

.. autoapisummary::

   TARANG.lib.time_advance.time_advance_chaos.dev1


Functions
---------

.. autoapisummary::

   TARANG.lib.time_advance.time_advance_chaos.compute_rhs_chaos
   TARANG.lib.time_advance.time_advance_chaos.time_adv_single_step_chaos_1
   TARANG.lib.time_advance.time_advance_chaos.time_adv_single_step_chaos_2
   TARANG.lib.time_advance.time_advance_chaos.time_advance_RK2_chaos
   TARANG.lib.time_advance.time_advance_chaos.Compute_RK4_parts_chaos_1
   TARANG.lib.time_advance.time_advance_chaos.Compute_RK4_parts_chaos_2
   TARANG.lib.time_advance.time_advance_chaos.time_advance_RK4_chaos


Module Contents
---------------

.. py:data:: dev1

.. py:function:: compute_rhs_chaos(t, U, P, T, univ)

.. py:function:: time_adv_single_step_chaos_1(a, b, c, U1, T1, univ1)

.. py:function:: time_adv_single_step_chaos_2(a, b, c, U2, T2, univ2)

.. py:function:: time_advance_RK2_chaos(U1, P1, T1, U2, P2, T, univ1, univ2)

.. py:function:: Compute_RK4_parts_chaos_1(b, factor, U1, T1, univ1)

.. py:function:: Compute_RK4_parts_chaos_2(b, factor, U2, T2, univ2)

.. py:function:: time_advance_RK4_chaos(U1, P1, T1, U2, P2, T2, univ1, univ2)

