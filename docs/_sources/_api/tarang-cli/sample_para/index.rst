tarang-cli.sample_para
======================

.. py:module:: tarang-cli.sample_para

.. autoapi-nested-parse::

   This script sets up and configures the parameters for running various types of simulations (e.g., hydrodynamic, magnetohydrodynamic, scalar) on either CPU or GPU.



Attributes
----------

.. autoapisummary::

   tarang-cli.sample_para.device
   tarang-cli.sample_para.device_rank
   tarang-cli.sample_para.complex_dtype
   tarang-cli.sample_para.real_dtype
   tarang-cli.sample_para.kind
   tarang-cli.sample_para.para_dir
   tarang-cli.sample_para.INPUT_SET_CASE
   tarang-cli.sample_para.input_case
   tarang-cli.sample_para.INPUT_ELSASSER
   tarang-cli.sample_para.INPUT_REAL_FIELD
   tarang-cli.sample_para.OUTPUT_REAL_FIELD
   tarang-cli.sample_para.INPUT_FROM_FILE
   tarang-cli.sample_para.input_file_name
   tarang-cli.sample_para.input_dir
   tarang-cli.sample_para.output_dir
   tarang-cli.sample_para.dimension
   tarang-cli.sample_para.Nx
   tarang-cli.sample_para.Ny
   tarang-cli.sample_para.Nz
   tarang-cli.sample_para.Ny
   tarang-cli.sample_para.L
   tarang-cli.sample_para.BOX_SIZE_DEFAULT
   tarang-cli.sample_para.L
   tarang-cli.sample_para.Rac
   tarang-cli.sample_para.Ra
   tarang-cli.sample_para.Pr
   tarang-cli.sample_para.kappa
   tarang-cli.sample_para.nu
   tarang-cli.sample_para.eta
   tarang-cli.sample_para.kappa
   tarang-cli.sample_para.HYPO_DISSIPATION
   tarang-cli.sample_para.HYPER_DISSIPATION
   tarang-cli.sample_para.nu_hypo
   tarang-cli.sample_para.nu_hypo_power
   tarang-cli.sample_para.nu_hypo_cutoff
   tarang-cli.sample_para.nu_hyper
   tarang-cli.sample_para.nu_hyper_power
   tarang-cli.sample_para.eta_hypo
   tarang-cli.sample_para.eta_hypo_power
   tarang-cli.sample_para.eta_hypo_cutoff
   tarang-cli.sample_para.eta_hyper
   tarang-cli.sample_para.eta_hyper_power
   tarang-cli.sample_para.kappa_hypo
   tarang-cli.sample_para.kappa_hypo_power
   tarang-cli.sample_para.kappa_hypo_cutoff
   tarang-cli.sample_para.kappa_hyper
   tarang-cli.sample_para.kappa_hyper_power
   tarang-cli.sample_para.FORCING_ENABLED
   tarang-cli.sample_para.FORCING_SCHEME
   tarang-cli.sample_para.RANDOM_FORCING_TYPE
   tarang-cli.sample_para.forcing_range
   tarang-cli.sample_para.injections
   tarang-cli.sample_para.BUOYANCY_ENABLED
   tarang-cli.sample_para.Nb
   tarang-cli.sample_para.ROTATION_ENABLED
   tarang-cli.sample_para.Omega
   tarang-cli.sample_para.MAINTAIN_FIELD
   tarang-cli.sample_para.maintain_mux
   tarang-cli.sample_para.time_scheme
   tarang-cli.sample_para.t_initial
   tarang-cli.sample_para.t_final
   tarang-cli.sample_para.dt
   tarang-cli.sample_para.FIXED_DT
   tarang-cli.sample_para.Courant_no
   tarang-cli.sample_para.t_eps
   tarang-cli.sample_para.PRINT_PARAMETERS
   tarang-cli.sample_para.RUNTIME_SAVE
   tarang-cli.sample_para.LIVE_PLOT
   tarang-cli.sample_para.USE_BINDING
   tarang-cli.sample_para.PLANAR_SPECTRA
   tarang-cli.sample_para.SAVE_VORTICITY
   tarang-cli.sample_para.SAVE_VECPOT
   tarang-cli.sample_para.modes_save
   tarang-cli.sample_para.iter_field_save_start
   tarang-cli.sample_para.iter_field_save_inter
   tarang-cli.sample_para.iter_field_save_buffer
   tarang-cli.sample_para.iter_glob_energy_print_start
   tarang-cli.sample_para.iter_glob_energy_print_inter
   tarang-cli.sample_para.iter_glob_save_buffer
   tarang-cli.sample_para.iter_ekTk_save_start
   tarang-cli.sample_para.iter_ekTk_save_inter
   tarang-cli.sample_para.iter_ekTk_save_buffer
   tarang-cli.sample_para.iter_modes_save_start
   tarang-cli.sample_para.iter_modes_save_inter
   tarang-cli.sample_para.iter_modes_save_buffer
   tarang-cli.sample_para.VALIDATE_SOLVER


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
   :value: 'HYDRO'


.. py:data:: para_dir

.. py:data:: INPUT_SET_CASE
   :value: True


.. py:data:: input_case
   :value: 'taylor_green'


.. py:data:: INPUT_ELSASSER
   :value: False


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


.. py:data:: eta
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


.. py:data:: eta_hypo
   :value: 1


.. py:data:: eta_hypo_power
   :value: -2


.. py:data:: eta_hypo_cutoff
   :value: -1


.. py:data:: eta_hyper
   :value: 0.0001


.. py:data:: eta_hyper_power
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


.. py:data:: injections
   :value: [0, 0, 0]


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
   :value: False


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


