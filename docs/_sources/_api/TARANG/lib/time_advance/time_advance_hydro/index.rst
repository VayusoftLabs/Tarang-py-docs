TARANG.lib.time_advance.time_advance_hydro
==========================================

.. py:module:: TARANG.lib.time_advance.time_advance_hydro


Functions
---------

.. autoapisummary::

   TARANG.lib.time_advance.time_advance_hydro.compute_rhs_hydro
   TARANG.lib.time_advance.time_advance_hydro.loop_breaker
   TARANG.lib.time_advance.time_advance_hydro.time_adv_single_step_hydro
   TARANG.lib.time_advance.time_advance_hydro.time_advance_Euler_hydro
   TARANG.lib.time_advance.time_advance_hydro.time_advance_RK2_hydro
   TARANG.lib.time_advance.time_advance_hydro.compute_RK4_parts_hydro
   TARANG.lib.time_advance.time_advance_hydro.time_advance_RK4_hydro


Module Contents
---------------

.. py:function:: compute_rhs_hydro(para, t, U, P, univ)

   Compute the right-hand side (RHS) for the hydrodynamic field.

   :param t: Current time.
   :type t: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param P: Pressure object representing the pressure field.
   :type P: Pressure
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: loop_breaker(para, U, univ)

   Check if the loop should be broken based on certain conditions.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :returns: True if the loop should be broken, False otherwise.
   :rtype: bool


.. py:function:: time_adv_single_step_hydro(para, a, b, c, U, univ)

   Perform a single time advancement step for the hydrodynamic field.

   :param a: Coefficient for the time advancement scheme.
   :type a: float
   :param b: Coefficient for the time advancement scheme.
   :type b: float
   :param c: Coefficient for the time advancement scheme.
   :type c: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: time_advance_Euler_hydro(para, U, P, univ)

   Perform time advancement using the Euler method for the hydrodynamic field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param P: Pressure object representing the pressure field.
   :type P: Pressure
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: time_advance_RK2_hydro(para, U, P, univ)

   Perform time advancement using the second-order Runge-Kutta (RK2) method for the hydrodynamic field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param P: Pressure object representing the pressure field.
   :type P: Pressure
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: compute_RK4_parts_hydro(para, b, factor, U, univ)

   Compute the parts for the fourth-order Runge-Kutta (RK4) method for the hydrodynamic field.

   :param b: Coefficient for the time advancement scheme.
   :type b: float
   :param factor: Factor for the time advancement scheme.
   :type factor: float
   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: time_advance_RK4_hydro(para, U, P, univ)

   Perform time advancement using the fourth-order Runge-Kutta (RK4) method for the hydrodynamic field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param P: Pressure object representing the pressure field.
   :type P: Pressure
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


