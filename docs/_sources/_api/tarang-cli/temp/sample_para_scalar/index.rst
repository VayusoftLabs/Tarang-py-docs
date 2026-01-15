tarang-cli.temp.sample_para_scalar
==================================

.. py:module:: tarang-cli.temp.sample_para_scalar

.. autoapi-nested-parse::

   This script sets up and configures the parameters for running various types of simulations (e.g., hydrodynamic, magnetohydrodynamic, scalar) on either CPU or GPU.



Attributes
----------

.. autoapisummary::

   tarang-cli.temp.sample_para_scalar.device
   tarang-cli.temp.sample_para_scalar.device_rank
   tarang-cli.temp.sample_para_scalar.complex_dtype
   tarang-cli.temp.sample_para_scalar.real_dtype
   tarang-cli.temp.sample_para_scalar.kind
   tarang-cli.temp.sample_para_scalar.para_dir
   tarang-cli.temp.sample_para_scalar.INPUT_SET_CASE
   tarang-cli.temp.sample_para_scalar.input_case
   tarang-cli.temp.sample_para_scalar.INPUT_REAL_FIELD
   tarang-cli.temp.sample_para_scalar.OUTPUT_REAL_FIELD
   tarang-cli.temp.sample_para_scalar.INPUT_FROM_FILE
   tarang-cli.temp.sample_para_scalar.input_file_name
   tarang-cli.temp.sample_para_scalar.input_dir
   tarang-cli.temp.sample_para_scalar.output_dir
   tarang-cli.temp.sample_para_scalar.dimension
   tarang-cli.temp.sample_para_scalar.Nx
   tarang-cli.temp.sample_para_scalar.Ny
   tarang-cli.temp.sample_para_scalar.Nz
   tarang-cli.temp.sample_para_scalar.Ny
   tarang-cli.temp.sample_para_scalar.L
   tarang-cli.temp.sample_para_scalar.BOX_SIZE_DEFAULT
   tarang-cli.temp.sample_para_scalar.L
   tarang-cli.temp.sample_para_scalar.Rac
   tarang-cli.temp.sample_para_scalar.Ra
   tarang-cli.temp.sample_para_scalar.Pr
   tarang-cli.temp.sample_para_scalar.kappa
   tarang-cli.temp.sample_para_scalar.nu
   tarang-cli.temp.sample_para_scalar.kappa
   tarang-cli.temp.sample_para_scalar.HYPO_DISSIPATION
   tarang-cli.temp.sample_para_scalar.HYPER_DISSIPATION
   tarang-cli.temp.sample_para_scalar.nu_hypo
   tarang-cli.temp.sample_para_scalar.nu_hypo_power
   tarang-cli.temp.sample_para_scalar.nu_hypo_cutoff
   tarang-cli.temp.sample_para_scalar.nu_hyper
   tarang-cli.temp.sample_para_scalar.nu_hyper_power
   tarang-cli.temp.sample_para_scalar.kappa_hypo
   tarang-cli.temp.sample_para_scalar.kappa_hypo_power
   tarang-cli.temp.sample_para_scalar.kappa_hypo_cutoff
   tarang-cli.temp.sample_para_scalar.kappa_hyper
   tarang-cli.temp.sample_para_scalar.kappa_hyper_power
   tarang-cli.temp.sample_para_scalar.FORCING_ENABLED
   tarang-cli.temp.sample_para_scalar.FORCING_SCHEME
   tarang-cli.temp.sample_para_scalar.RANDOM_FORCING_TYPE
   tarang-cli.temp.sample_para_scalar.forcing_range
   tarang-cli.temp.sample_para_scalar.BUOYANCY_ENABLED
   tarang-cli.temp.sample_para_scalar.Nb
   tarang-cli.temp.sample_para_scalar.ROTATION_ENABLED
   tarang-cli.temp.sample_para_scalar.Omega
   tarang-cli.temp.sample_para_scalar.MAINTAIN_FIELD
   tarang-cli.temp.sample_para_scalar.maintain_mux
   tarang-cli.temp.sample_para_scalar.time_scheme
   tarang-cli.temp.sample_para_scalar.t_initial
   tarang-cli.temp.sample_para_scalar.t_final
   tarang-cli.temp.sample_para_scalar.dt
   tarang-cli.temp.sample_para_scalar.FIXED_DT
   tarang-cli.temp.sample_para_scalar.Courant_no
   tarang-cli.temp.sample_para_scalar.t_eps
   tarang-cli.temp.sample_para_scalar.PRINT_PARAMETERS
   tarang-cli.temp.sample_para_scalar.RUNTIME_SAVE
   tarang-cli.temp.sample_para_scalar.LIVE_PLOT
   tarang-cli.temp.sample_para_scalar.USE_BINDING
   tarang-cli.temp.sample_para_scalar.PLANAR_SPECTRA
   tarang-cli.temp.sample_para_scalar.SAVE_VORTICITY
   tarang-cli.temp.sample_para_scalar.SAVE_VECPOT
   tarang-cli.temp.sample_para_scalar.modes_save
   tarang-cli.temp.sample_para_scalar.iter_field_save_start
   tarang-cli.temp.sample_para_scalar.iter_field_save_inter
   tarang-cli.temp.sample_para_scalar.iter_field_save_buffer
   tarang-cli.temp.sample_para_scalar.iter_glob_energy_print_start
   tarang-cli.temp.sample_para_scalar.iter_glob_energy_print_inter
   tarang-cli.temp.sample_para_scalar.iter_glob_save_buffer
   tarang-cli.temp.sample_para_scalar.iter_ekTk_save_start
   tarang-cli.temp.sample_para_scalar.iter_ekTk_save_inter
   tarang-cli.temp.sample_para_scalar.iter_ekTk_save_buffer
   tarang-cli.temp.sample_para_scalar.iter_modes_save_start
   tarang-cli.temp.sample_para_scalar.iter_modes_save_inter
   tarang-cli.temp.sample_para_scalar.iter_modes_save_buffer
   tarang-cli.temp.sample_para_scalar.VALIDATE_SOLVER
   tarang-cli.temp.sample_para_scalar.injections


Module Contents
---------------

.. py:data:: device
   :value: 'CPU'


.. py:data:: device_rank
   :value: 0


.. py:data:: complex_dtype
   :value: 'complex'


.. py:data:: real_dtype
   :value: 'float64'


.. py:data:: kind
   :value: 'SCALAR'


.. py:data:: para_dir

.. py:data:: INPUT_SET_CASE
   :value: True


.. py:data:: input_case
   :value: 'custom'


.. py:data:: INPUT_REAL_FIELD
   :value: False


.. py:data:: OUTPUT_REAL_FIELD
   :value: False


.. py:data:: INPUT_FROM_FILE
   :value: False


.. py:data:: input_file_name
   :value: 'init_cond.h5'


.. py:data:: input_dir
   :value: 'Uninferable/input'


.. py:data:: output_dir
   :value: 'Uninferable/output'


.. py:data:: dimension
   :value: 2


.. py:data:: Nx
   :value: 128


.. py:data:: Ny
   :value: 128


.. py:data:: Nz
   :value: 128


.. py:data:: Ny
   :value: 1


.. py:data:: L
   :value: [10, 10, 10]


.. py:data:: BOX_SIZE_DEFAULT
   :value: True


.. py:data:: L

.. py:data:: Rac

.. py:data:: Ra

.. py:data:: Pr
   :value: 6.8


.. py:data:: kappa

.. py:data:: nu
   :value: 0.02


.. py:data:: kappa
   :value: 0.02


.. py:data:: HYPO_DISSIPATION
   :value: False


.. py:data:: HYPER_DISSIPATION
   :value: False


.. py:data:: nu_hypo
   :value: 1


.. py:data:: nu_hypo_power
   :value: -2


.. py:data:: nu_hypo_cutoff
   :value: -1


.. py:data:: nu_hyper
   :value: 0.0001


.. py:data:: nu_hyper_power
   :value: 2


.. py:data:: kappa_hypo
   :value: 1


.. py:data:: kappa_hypo_power
   :value: -2


.. py:data:: kappa_hypo_cutoff
   :value: -1


.. py:data:: kappa_hyper
   :value: 0.0001


.. py:data:: kappa_hyper_power
   :value: 2


.. py:data:: FORCING_ENABLED
   :value: False


.. py:data:: FORCING_SCHEME
   :value: 'random'


.. py:data:: RANDOM_FORCING_TYPE
   :value: 'u'


.. py:data:: forcing_range
   :value: [2, 3]


.. py:data:: BUOYANCY_ENABLED
   :value: False


.. py:data:: Nb
   :value: 0


.. py:data:: ROTATION_ENABLED
   :value: False


.. py:data:: Omega
   :value: [0, 0, 0]


.. py:data:: MAINTAIN_FIELD
   :value: False


.. py:data:: maintain_mux
   :value: 1


.. py:data:: time_scheme
   :value: 'RK4'


.. py:data:: t_initial
   :value: 0


.. py:data:: t_final
   :value: 1


.. py:data:: dt
   :value: 0.001


.. py:data:: FIXED_DT
   :value: False


.. py:data:: Courant_no
   :value: 0.1


.. py:data:: t_eps
   :value: 1e-08


.. py:data:: PRINT_PARAMETERS
   :value: True


.. py:data:: RUNTIME_SAVE
   :value: True


.. py:data:: LIVE_PLOT
   :value: False


.. py:data:: USE_BINDING
   :value: False


.. py:data:: PLANAR_SPECTRA
   :value: False


.. py:data:: SAVE_VORTICITY
   :value: False


.. py:data:: SAVE_VECPOT
   :value: False


.. py:data:: modes_save
   :value: []


.. py:data:: iter_field_save_start
   :value: 0


.. py:data:: iter_field_save_inter
   :value: 1000


.. py:data:: iter_field_save_buffer
   :value: 1


.. py:data:: iter_glob_energy_print_start
   :value: 0


.. py:data:: iter_glob_energy_print_inter
   :value: 1


.. py:data:: iter_glob_save_buffer
   :value: 100


.. py:data:: iter_ekTk_save_start
   :value: 0


.. py:data:: iter_ekTk_save_inter
   :value: 10


.. py:data:: iter_ekTk_save_buffer
   :value: 100


.. py:data:: iter_modes_save_start
   :value: 0


.. py:data:: iter_modes_save_inter
   :value: 100


.. py:data:: iter_modes_save_buffer
   :value: 1


.. py:data:: VALIDATE_SOLVER
   :value: False


.. py:data:: injections

