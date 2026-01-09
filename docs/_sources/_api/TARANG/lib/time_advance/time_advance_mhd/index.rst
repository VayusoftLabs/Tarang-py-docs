TARANG.lib.time_advance.time_advance_mhd
========================================

.. py:module:: TARANG.lib.time_advance.time_advance_mhd


Functions
---------

.. autoapisummary::

   TARANG.lib.time_advance.time_advance_mhd.compute_rhs_mhd
   TARANG.lib.time_advance.time_advance_mhd.loop_breaker
   TARANG.lib.time_advance.time_advance_mhd.time_adv_single_step_mhd
   TARANG.lib.time_advance.time_advance_mhd.time_advance_Euler_mhd
   TARANG.lib.time_advance.time_advance_mhd.time_advance_RK2_mhd
   TARANG.lib.time_advance.time_advance_mhd.compute_RK4_parts_mhd
   TARANG.lib.time_advance.time_advance_mhd.time_advance_RK4_mhd


Module Contents
---------------

.. py:function:: compute_rhs_mhd(para, t, U, B, P, univ)

   Compute the right-hand side (RHS) for the magnetohydrodynamic (MHD) field.

   :param t: Current time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField
   :param P: Pressure object representing the pressure field.
   :type P: Pressure
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: loop_breaker(para, U, B, univ)

   Check if the loop should be broken based on certain conditions.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :returns: True if the loop should be broken, False otherwise.
   :rtype: bool


.. py:function:: time_adv_single_step_mhd(para, a, b, c, U, B, univ)

   Perform a single time advancement step for the magnetohydrodynamic (MHD) field.

   :param a: Coefficient for the time advancement scheme.
   :type a: float
   :param b: Coefficient for the time advancement scheme.
   :type b: float
   :param c: Coefficient for the time advancement scheme.
   :type c: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: time_advance_Euler_mhd(para, U, B, P, univ)

   Perform time advancement using the Euler method for the magnetohydrodynamic field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField
   :param P: Pressure object representing the pressure field.
   :type P: Pressure
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: time_advance_RK2_mhd(para, U, B, P, univ)

   Perform time advancement using the second-order Runge-Kutta (RK2) method for the magnetohydrodynamic field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField
   :param P: Pressure object representing the pressure field.
   :type P: Pressure
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: compute_RK4_parts_mhd(para, b, factor, U, B, univ)

   Compute the parts for the fourth-order Runge-Kutta (RK4) method for the magnetohydrodynamic field.

   :param b: Coefficient for the time advancement scheme.
   :type b: float
   :param factor: Factor for the time advancement scheme.
   :type factor: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: time_advance_RK4_mhd(para, U, B, P, univ)

   Perform time advancement using the fourth-order Runge-Kutta (RK4) method for the magnetohydrodynamic field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField
   :param P: Pressure object representing the pressure field.
   :type P: Pressure
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


