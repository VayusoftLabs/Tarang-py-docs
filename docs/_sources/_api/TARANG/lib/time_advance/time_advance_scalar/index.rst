TARANG.lib.time_advance.time_advance_scalar
===========================================

.. py:module:: TARANG.lib.time_advance.time_advance_scalar


Functions
---------

.. autoapisummary::

   TARANG.lib.time_advance.time_advance_scalar.compute_rhs_scalar
   TARANG.lib.time_advance.time_advance_scalar.loop_breaker
   TARANG.lib.time_advance.time_advance_scalar.time_adv_single_step_scalar
   TARANG.lib.time_advance.time_advance_scalar.time_advance_Euler_scalar
   TARANG.lib.time_advance.time_advance_scalar.time_advance_RK2_scalar
   TARANG.lib.time_advance.time_advance_scalar.compute_RK4_parts_scalar
   TARANG.lib.time_advance.time_advance_scalar.time_advance_RK4_scalar


Module Contents
---------------

.. py:function:: compute_rhs_scalar(para, t, U, T, P, univ)

   Compute the right-hand side (RHS) for the scalar field.

   :param t: Current time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param T: ScalarField object representing the scalar field.
   :type T: ScalarField
   :param P: Pressure object representing the pressure field.
   :type P: Pressure
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: loop_breaker(para, U, T, univ)

   Check if the loop should be broken based on certain conditions.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param T: ScalarField object representing the scalar field.
   :type T: ScalarField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :returns: True if the loop should be broken, False otherwise.
   :rtype: bool


.. py:function:: time_adv_single_step_scalar(para, a, b, c, U, T, univ)

   Perform a single time advancement step for the scalar field.

   :param a: Coefficient for the time advancement scheme.
   :type a: float
   :param b: Coefficient for the time advancement scheme.
   :type b: float
   :param c: Coefficient for the time advancement scheme.
   :type c: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param T: ScalarField object representing the scalar field.
   :type T: ScalarField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: time_advance_Euler_scalar(para, U, T, P, univ)

   Perform time advancement using the Euler method for the scalar field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param T: ScalarField object representing the scalar field.
   :type T: ScalarField
   :param P: Pressure object representing the pressure field.
   :type P: Pressure
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: time_advance_RK2_scalar(para, U, T, P, univ)

   Perform time advancement using the second-order Runge-Kutta (RK2) method for the scalar field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param T: ScalarField object representing the scalar field.
   :type T: ScalarField
   :param P: Pressure object representing the pressure field.
   :type P: Pressure
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: compute_RK4_parts_scalar(para, b, factor, U, T, univ)

   Compute the parts for the fourth-order Runge-Kutta (RK4) method for the scalar field.

   :param b: Coefficient for the time advancement scheme.
   :type b: float
   :param factor: Factor for the time advancement scheme.
   :type factor: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param T: ScalarField object representing the scalar field.
   :type T: ScalarField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: time_advance_RK4_scalar(para, U, T, P, univ)

   Perform time advancement using the fourth-order Runge-Kutta (RK4) method for the scalar field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param T: ScalarField object representing the scalar field.
   :type T: ScalarField
   :param P: Pressure object representing the pressure field.
   :type P: Pressure
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


