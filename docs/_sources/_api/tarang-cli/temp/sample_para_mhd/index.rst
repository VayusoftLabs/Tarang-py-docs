tarang-cli.temp.sample_para_mhd
===============================

.. py:module:: tarang-cli.temp.sample_para_mhd

.. autoapi-nested-parse::

   This script sets up and configures the parameters for running various types of simulations (e.g., hydrodynamic, magnetohydrodynamic, scalar) on either CPU or GPU.



Attributes
----------

.. autoapisummary::

   tarang-cli.temp.sample_para_mhd.device
   tarang-cli.temp.sample_para_mhd.device_rank
   tarang-cli.temp.sample_para_mhd.complex_dtype
   tarang-cli.temp.sample_para_mhd.real_dtype
   tarang-cli.temp.sample_para_mhd.kind
   tarang-cli.temp.sample_para_mhd.para_dir
   tarang-cli.temp.sample_para_mhd.INPUT_SET_CASE
   tarang-cli.temp.sample_para_mhd.input_case
   tarang-cli.temp.sample_para_mhd.INPUT_ELSASSER
   tarang-cli.temp.sample_para_mhd.INPUT_REAL_FIELD
   tarang-cli.temp.sample_para_mhd.OUTPUT_REAL_FIELD
   tarang-cli.temp.sample_para_mhd.INPUT_FROM_FILE
   tarang-cli.temp.sample_para_mhd.input_file_name
   tarang-cli.temp.sample_para_mhd.input_dir
   tarang-cli.temp.sample_para_mhd.output_dir
   tarang-cli.temp.sample_para_mhd.dimension
   tarang-cli.temp.sample_para_mhd.Nx
   tarang-cli.temp.sample_para_mhd.Ny
   tarang-cli.temp.sample_para_mhd.Nz
   tarang-cli.temp.sample_para_mhd.Ny
   tarang-cli.temp.sample_para_mhd.L
   tarang-cli.temp.sample_para_mhd.BOX_SIZE_DEFAULT
   tarang-cli.temp.sample_para_mhd.L
   tarang-cli.temp.sample_para_mhd.Rac
   tarang-cli.temp.sample_para_mhd.Ra
   tarang-cli.temp.sample_para_mhd.Pr
   tarang-cli.temp.sample_para_mhd.kappa
   tarang-cli.temp.sample_para_mhd.nu
   tarang-cli.temp.sample_para_mhd.eta
   tarang-cli.temp.sample_para_mhd.HYPO_DISSIPATION
   tarang-cli.temp.sample_para_mhd.HYPER_DISSIPATION
   tarang-cli.temp.sample_para_mhd.nu_hypo
   tarang-cli.temp.sample_para_mhd.nu_hypo_power
   tarang-cli.temp.sample_para_mhd.nu_hypo_cutoff
   tarang-cli.temp.sample_para_mhd.nu_hyper
   tarang-cli.temp.sample_para_mhd.nu_hyper_power
   tarang-cli.temp.sample_para_mhd.eta_hypo
   tarang-cli.temp.sample_para_mhd.eta_hypo_power
   tarang-cli.temp.sample_para_mhd.eta_hypo_cutoff
   tarang-cli.temp.sample_para_mhd.eta_hyper
   tarang-cli.temp.sample_para_mhd.eta_hyper_power
   tarang-cli.temp.sample_para_mhd.FORCING_ENABLED
   tarang-cli.temp.sample_para_mhd.FORCING_SCHEME
   tarang-cli.temp.sample_para_mhd.forcing_range
   tarang-cli.temp.sample_para_mhd.injection_plus
   tarang-cli.temp.sample_para_mhd.injection_minus
   tarang-cli.temp.sample_para_mhd.injection_vector_potential
   tarang-cli.temp.sample_para_mhd.injection_magnetic_helicity
   tarang-cli.temp.sample_para_mhd.MAINTAIN_FIELD
   tarang-cli.temp.sample_para_mhd.maintain_mux
   tarang-cli.temp.sample_para_mhd.time_scheme
   tarang-cli.temp.sample_para_mhd.t_initial
   tarang-cli.temp.sample_para_mhd.t_final
   tarang-cli.temp.sample_para_mhd.dt
   tarang-cli.temp.sample_para_mhd.FIXED_DT
   tarang-cli.temp.sample_para_mhd.Courant_no
   tarang-cli.temp.sample_para_mhd.t_eps
   tarang-cli.temp.sample_para_mhd.PRINT_PARAMETERS
   tarang-cli.temp.sample_para_mhd.RUNTIME_SAVE
   tarang-cli.temp.sample_para_mhd.LIVE_PLOT
   tarang-cli.temp.sample_para_mhd.USE_BINDING
   tarang-cli.temp.sample_para_mhd.PLANAR_SPECTRA
   tarang-cli.temp.sample_para_mhd.SAVE_VORTICITY
   tarang-cli.temp.sample_para_mhd.SAVE_VECPOT
   tarang-cli.temp.sample_para_mhd.modes_save
   tarang-cli.temp.sample_para_mhd.iter_field_save_start
   tarang-cli.temp.sample_para_mhd.iter_field_save_inter
   tarang-cli.temp.sample_para_mhd.iter_field_save_buffer
   tarang-cli.temp.sample_para_mhd.iter_glob_energy_print_start
   tarang-cli.temp.sample_para_mhd.iter_glob_energy_print_inter
   tarang-cli.temp.sample_para_mhd.iter_glob_save_buffer
   tarang-cli.temp.sample_para_mhd.iter_ekTk_save_start
   tarang-cli.temp.sample_para_mhd.iter_ekTk_save_inter
   tarang-cli.temp.sample_para_mhd.iter_ekTk_save_buffer
   tarang-cli.temp.sample_para_mhd.iter_modes_save_start
   tarang-cli.temp.sample_para_mhd.iter_modes_save_inter
   tarang-cli.temp.sample_para_mhd.iter_modes_save_buffer
   tarang-cli.temp.sample_para_mhd.VALIDATE_SOLVER
   tarang-cli.temp.sample_para_mhd.injections


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
   :value: 'MHD'


.. py:data:: para_dir

.. py:data:: INPUT_SET_CASE
   :value: True


.. py:data:: input_case
   :value: 'custom'


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


.. py:data:: FORCING_ENABLED
   :value: False


.. py:data:: FORCING_SCHEME
   :value: 'random'


.. py:data:: forcing_range
   :value: [2, 3]


.. py:data:: injection_plus
   :value: 0.1


.. py:data:: injection_minus
   :value: 0.1


.. py:data:: injection_vector_potential
   :value: 0.01


.. py:data:: injection_magnetic_helicity
   :value: 0.01


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

