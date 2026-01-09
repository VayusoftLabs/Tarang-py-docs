TARANG.lib.global_fns.universal
===============================

.. py:module:: TARANG.lib.global_fns.universal


Classes
-------

.. autoapisummary::

   TARANG.lib.global_fns.universal.UniversalArrays


Module Contents
---------------

.. py:class:: UniversalArrays(para)

   Class representing universal arrays for the TARANG solver.

   .. attribute:: COMPUTE_NLIN_FIRST_FLAG

      Flag to indicate if nonlinear computation is first.

      :type: bool

   .. attribute:: COMPUTE_DT_FLAG

      Flag to indicate if time step computation is enabled.

      :type: bool

   .. attribute:: T_LAST

      Flag to indicate if the last time step is reached.

      :type: bool

   .. attribute:: dt_fixed

      Fixed time step.

      :type: float

   .. attribute:: dt

      Variable time step.

      :type: float

   .. attribute:: FORCE_PHASE_FIRST

      Flag to indicate if force phase is first.

      :type: bool

   .. attribute:: phase_ch1

      Phase for the forcing.

      :type: float

   .. attribute:: iter

      Iteration count.

      :type: int

   .. attribute:: ubydx

      Velocity by grid spacing.

      :type: float

   .. attribute:: exp_factor_array

      Array for exponential factors.

      :type: array-like

   .. attribute:: exp_factor_array_eta

      Array for exponential factors for magnetic diffusivity (MHD).

      :type: array-like

   .. attribute:: cross_helicity

      Array for cross helicity (MHD).

      :type: array-like

   .. attribute:: exp_factor_array_kappa

      Array for exponential factors for scalar diffusivity.

      :type: array-like

   .. attribute:: temp_nlin

      Temporary array for nonlinear terms.

      :type: array-like

   .. attribute:: temp1_RK

      Temporary array for Runge-Kutta scheme.

      :type: array-like

   .. attribute:: temp2_RK

      Temporary array for Runge-Kutta scheme.

      :type: array-like

   .. attribute:: temp3_RK

      Temporary array for Runge-Kutta scheme.

      :type: array-like

   .. attribute:: temp1b_RK

      Temporary array for Runge-Kutta scheme.

      :type: array-like

   .. attribute:: temp2b_RK

      Temporary array for Runge-Kutta scheme.

      :type: array-like

   .. attribute:: temp3b_RK

      Temporary array for Runge-Kutta scheme.

      :type: array-like

   .. attribute:: temp_scalar1_RK

      Temporary array for scalar Runge-Kutta scheme.

      :type: array-like

   .. attribute:: temp_scalar2_RK

      Temporary array for scalar Runge-Kutta scheme.

      :type: array-like

   .. attribute:: tempR

      Temporary real array.

      :type: array-like

   .. attribute:: dx

      Grid spacing in x direction.

      :type: float

   .. attribute:: dy

      Grid spacing in y direction.

      :type: float

   .. attribute:: dz

      Grid spacing in z direction.

      :type: float

   .. attribute:: t

      Array for time steps.

      :type: array-like

   .. attribute:: t_dt

      Array for time steps for dt.

      :type: array-like

   .. attribute:: t_field_save

      Array for time steps for field saving.

      :type: array-like

   .. attribute:: t_glob_energy_print

      Array for time steps for global energy printing.

      :type: array-like

   .. attribute:: t_ekTk_save

      Array for time steps for energy and transfer saving.

      :type: array-like

   .. attribute:: t_modes_save

      Array for time steps for modes saving.

      :type: array-like


   .. py:attribute:: para


   .. py:attribute:: COMPUTE_NLIN_FIRST_FLAG
      :value: None



   .. py:attribute:: COMPUTE_DT_FLAG
      :value: None



   .. py:attribute:: T_LAST
      :value: False



   .. py:attribute:: dt_fixed
      :value: 0



   .. py:attribute:: dt
      :value: 0



   .. py:attribute:: FORCE_PHASE_FIRST
      :value: None



   .. py:attribute:: phase_ch1
      :value: 0



   .. py:attribute:: iter
      :value: 0



   .. py:attribute:: ubydx
      :value: 0



   .. py:attribute:: exp_factor_array
      :value: []



   .. py:attribute:: temp_nlin
      :value: []



   .. py:attribute:: temp1_RK
      :value: []



   .. py:attribute:: temp2_RK
      :value: []



   .. py:attribute:: temp3_RK
      :value: []



   .. py:attribute:: temp1b_RK
      :value: []



   .. py:attribute:: temp2b_RK
      :value: []



   .. py:attribute:: temp3b_RK
      :value: []



   .. py:attribute:: temp_scalar1_RK
      :value: []



   .. py:attribute:: temp_scalar2_RK
      :value: []



   .. py:attribute:: tempR
      :value: []



   .. py:attribute:: dx
      :value: None



   .. py:attribute:: dy
      :value: None



   .. py:attribute:: dz
      :value: None



   .. py:attribute:: t
      :value: []



   .. py:attribute:: t_dt
      :value: []



   .. py:attribute:: t_field_save
      :value: []



   .. py:attribute:: t_glob_energy_print
      :value: []



   .. py:attribute:: t_ekTk_save
      :value: []



   .. py:attribute:: t_modes_save
      :value: []



   .. py:attribute:: t_buf
      :value: []



   .. py:attribute:: t_dt_buf
      :value: []



   .. py:method:: set_arrays()

      Set the arrays for the universal arrays based on the simulation parameters.



   .. py:method:: set_exp_arrays()

      Set the exponential factor arrays based on the simulation parameters.



   .. py:method:: set_grid_space()

      Set the grid spacing based on the simulation parameters.



