tarang-cli.validation.para_hydro
================================

.. py:module:: tarang-cli.validation.para_hydro

.. autoapi-nested-parse::

   This script sets up and configures the parameters for running various types of simulations (e.g., hydrodynamic, magnetohydrodynamic, scalar) on either CPU or GPU.



Attributes
----------

.. autoapisummary::

   tarang-cli.validation.para_hydro.device
   tarang-cli.validation.para_hydro.device_rank
   tarang-cli.validation.para_hydro.complex_dtype
   tarang-cli.validation.para_hydro.real_dtype
   tarang-cli.validation.para_hydro.kind
   tarang-cli.validation.para_hydro.para_dir
   tarang-cli.validation.para_hydro.INPUT_SET_CASE
   tarang-cli.validation.para_hydro.input_case
   tarang-cli.validation.para_hydro.INPUT_FROM_FILE
   tarang-cli.validation.para_hydro.INPUT_REAL_FIELD
   tarang-cli.validation.para_hydro.INPUT_ELSASSER
   tarang-cli.validation.para_hydro.input_file_name
   tarang-cli.validation.para_hydro.input_dir
   tarang-cli.validation.para_hydro.OUTPUT_REAL_FIELD
   tarang-cli.validation.para_hydro.output_dir
   tarang-cli.validation.para_hydro.dimension
   tarang-cli.validation.para_hydro.Nx
   tarang-cli.validation.para_hydro.Ny
   tarang-cli.validation.para_hydro.Nz
   tarang-cli.validation.para_hydro.Ny
   tarang-cli.validation.para_hydro.L
   tarang-cli.validation.para_hydro.BOX_SIZE_DEFAULT
   tarang-cli.validation.para_hydro.L
   tarang-cli.validation.para_hydro.Rac
   tarang-cli.validation.para_hydro.Ra
   tarang-cli.validation.para_hydro.Pr
   tarang-cli.validation.para_hydro.kappa
   tarang-cli.validation.para_hydro.nu
   tarang-cli.validation.para_hydro.eta
   tarang-cli.validation.para_hydro.kappa
   tarang-cli.validation.para_hydro.HYPO_DISSIPATION
   tarang-cli.validation.para_hydro.HYPER_DISSIPATION
   tarang-cli.validation.para_hydro.nu_hypo
   tarang-cli.validation.para_hydro.nu_hypo_power
   tarang-cli.validation.para_hydro.nu_hypo_cutoff
   tarang-cli.validation.para_hydro.nu_hyper
   tarang-cli.validation.para_hydro.nu_hyper_power
   tarang-cli.validation.para_hydro.eta_hypo
   tarang-cli.validation.para_hydro.eta_hypo_power
   tarang-cli.validation.para_hydro.eta_hypo_cutoff
   tarang-cli.validation.para_hydro.eta_hyper
   tarang-cli.validation.para_hydro.eta_hyper_power
   tarang-cli.validation.para_hydro.kappa_hypo
   tarang-cli.validation.para_hydro.kappa_hypo_power
   tarang-cli.validation.para_hydro.kappa_hypo_cutoff
   tarang-cli.validation.para_hydro.kappa_hyper
   tarang-cli.validation.para_hydro.kappa_hyper_power
   tarang-cli.validation.para_hydro.FORCING_ENABLED
   tarang-cli.validation.para_hydro.FORCING_SCHEME
   tarang-cli.validation.para_hydro.forcing_range
   tarang-cli.validation.para_hydro.injections
   tarang-cli.validation.para_hydro.BUOYANCY_ENABLED
   tarang-cli.validation.para_hydro.Nb
   tarang-cli.validation.para_hydro.ROTATION_ENABLED
   tarang-cli.validation.para_hydro.Omega
   tarang-cli.validation.para_hydro.MAINTAIN_FIELD
   tarang-cli.validation.para_hydro.maintain_mux
   tarang-cli.validation.para_hydro.time_scheme
   tarang-cli.validation.para_hydro.t_initial
   tarang-cli.validation.para_hydro.t_final
   tarang-cli.validation.para_hydro.dt
   tarang-cli.validation.para_hydro.FIXED_DT
   tarang-cli.validation.para_hydro.Courant_no
   tarang-cli.validation.para_hydro.t_eps
   tarang-cli.validation.para_hydro.PRINT_PARAMETERS
   tarang-cli.validation.para_hydro.RUNTIME_SAVE
   tarang-cli.validation.para_hydro.LIVE_PLOT
   tarang-cli.validation.para_hydro.USE_BINDING
   tarang-cli.validation.para_hydro.PLANAR_SPECTRA
   tarang-cli.validation.para_hydro.SAVE_VORTICITY
   tarang-cli.validation.para_hydro.SAVE_VECPOT
   tarang-cli.validation.para_hydro.modes_save
   tarang-cli.validation.para_hydro.iter_field_save_start
   tarang-cli.validation.para_hydro.iter_field_save_inter
   tarang-cli.validation.para_hydro.iter_glob_energy_print_start
   tarang-cli.validation.para_hydro.iter_glob_energy_print_inter
   tarang-cli.validation.para_hydro.iter_ekTk_save_start
   tarang-cli.validation.para_hydro.iter_ekTk_save_inter
   tarang-cli.validation.para_hydro.iter_modes_save_start
   tarang-cli.validation.para_hydro.iter_modes_save_inter
   tarang-cli.validation.para_hydro.VALIDATE_SOLVER


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
   :value: 'benchmark'


.. py:data:: INPUT_FROM_FILE
   :value: False


.. py:data:: INPUT_REAL_FIELD
   :value: False


.. py:data:: INPUT_ELSASSER
   :value: False


.. py:data:: input_file_name
   :value: 'init_cond.h5'


.. py:data:: input_dir
   :value: 'Uninferable/input'


.. py:data:: OUTPUT_REAL_FIELD
   :value: False


.. py:data:: output_dir
   :value: 'Uninferable/output'


.. py:data:: dimension
   :value: 3


.. py:data:: Nx
   :value: 64


.. py:data:: Ny
   :value: 64


.. py:data:: Nz
   :value: 64


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
   :value: True


.. py:data:: HYPER_DISSIPATION
   :value: True


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


.. py:data:: forcing_range
   :value: [4, 5]


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
   :value: 50


.. py:data:: dt
   :value: 0.001


.. py:data:: FIXED_DT
   :value: False


.. py:data:: Courant_no
   :value: 0.5


.. py:data:: t_eps
   :value: 1e-08


.. py:data:: PRINT_PARAMETERS
   :value: True


.. py:data:: RUNTIME_SAVE
   :value: True


.. py:data:: LIVE_PLOT
   :value: False


.. py:data:: USE_BINDING
   :value: True


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


.. py:data:: iter_glob_energy_print_start
   :value: 0


.. py:data:: iter_glob_energy_print_inter
   :value: 1


.. py:data:: iter_ekTk_save_start
   :value: 0


.. py:data:: iter_ekTk_save_inter
   :value: 10


.. py:data:: iter_modes_save_start
   :value: 0


.. py:data:: iter_modes_save_inter
   :value: 100


.. py:data:: VALIDATE_SOLVER
   :value: False


