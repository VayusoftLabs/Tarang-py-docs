TARANG.lib.valid.val_para
=========================

.. py:module:: TARANG.lib.valid.val_para


Attributes
----------

.. autoapisummary::

   TARANG.lib.valid.val_para.device
   TARANG.lib.valid.val_para.device_rank
   TARANG.lib.valid.val_para.complex_dtype
   TARANG.lib.valid.val_para.real_dtype
   TARANG.lib.valid.val_para.kind
   TARANG.lib.valid.val_para.INPUT_SET_CASE
   TARANG.lib.valid.val_para.input_case
   TARANG.lib.valid.val_para.INPUT_ELSASSER
   TARANG.lib.valid.val_para.INPUT_REAL_FIELD
   TARANG.lib.valid.val_para.OUTPUT_REAL_FIELD
   TARANG.lib.valid.val_para.INPUT_FROM_FILE
   TARANG.lib.valid.val_para.input_file_name
   TARANG.lib.valid.val_para.input_dir
   TARANG.lib.valid.val_para.output_dir
   TARANG.lib.valid.val_para.dimension
   TARANG.lib.valid.val_para.Nx
   TARANG.lib.valid.val_para.Ny
   TARANG.lib.valid.val_para.Nz
   TARANG.lib.valid.val_para.L
   TARANG.lib.valid.val_para.BOX_SIZE_DEFAULT
   TARANG.lib.valid.val_para.L
   TARANG.lib.valid.val_para.Rac
   TARANG.lib.valid.val_para.Ra
   TARANG.lib.valid.val_para.Pr
   TARANG.lib.valid.val_para.kappa
   TARANG.lib.valid.val_para.nu
   TARANG.lib.valid.val_para.eta
   TARANG.lib.valid.val_para.kappa
   TARANG.lib.valid.val_para.HYPO_DISSIPATION
   TARANG.lib.valid.val_para.HYPER_DISSIPATION
   TARANG.lib.valid.val_para.nu_hypo
   TARANG.lib.valid.val_para.nu_hypo_power
   TARANG.lib.valid.val_para.nu_hypo_cutoff
   TARANG.lib.valid.val_para.nu_hyper
   TARANG.lib.valid.val_para.nu_hyper_power
   TARANG.lib.valid.val_para.eta_hypo
   TARANG.lib.valid.val_para.eta_hypo_power
   TARANG.lib.valid.val_para.eta_hypo_cutoff
   TARANG.lib.valid.val_para.eta_hyper
   TARANG.lib.valid.val_para.eta_hyper_power
   TARANG.lib.valid.val_para.kappa_hypo
   TARANG.lib.valid.val_para.kappa_hypo_power
   TARANG.lib.valid.val_para.kappa_hypo_cutoff
   TARANG.lib.valid.val_para.kappa_hyper
   TARANG.lib.valid.val_para.kappa_hyper_power
   TARANG.lib.valid.val_para.FORCING_ENABLED
   TARANG.lib.valid.val_para.FORCING_SCHEME
   TARANG.lib.valid.val_para.forcing_range
   TARANG.lib.valid.val_para.injection_u
   TARANG.lib.valid.val_para.injection_h
   TARANG.lib.valid.val_para.injection_plus
   TARANG.lib.valid.val_para.injection_minus
   TARANG.lib.valid.val_para.injection_vector_potential
   TARANG.lib.valid.val_para.injection_magnetic_helicity
   TARANG.lib.valid.val_para.BUOYANCY_ENABLED
   TARANG.lib.valid.val_para.Nb
   TARANG.lib.valid.val_para.ROTATION_ENABLED
   TARANG.lib.valid.val_para.Omega
   TARANG.lib.valid.val_para.MAINTAIN_FIELD
   TARANG.lib.valid.val_para.maintain_mux
   TARANG.lib.valid.val_para.time_scheme
   TARANG.lib.valid.val_para.t_initial
   TARANG.lib.valid.val_para.t_final
   TARANG.lib.valid.val_para.dt
   TARANG.lib.valid.val_para.FIXED_DT
   TARANG.lib.valid.val_para.Courant_no
   TARANG.lib.valid.val_para.t_eps
   TARANG.lib.valid.val_para.PRINT_PARAMETERS
   TARANG.lib.valid.val_para.RUNTIME_SAVE
   TARANG.lib.valid.val_para.LIVE_PLOT
   TARANG.lib.valid.val_para.USE_BINDING
   TARANG.lib.valid.val_para.PLANAR_SPECTRA
   TARANG.lib.valid.val_para.SAVE_VORTICITY
   TARANG.lib.valid.val_para.SAVE_VECPOT
   TARANG.lib.valid.val_para.modes_save
   TARANG.lib.valid.val_para.iter_field_save_start
   TARANG.lib.valid.val_para.iter_field_save_inter
   TARANG.lib.valid.val_para.iter_field_save_buffer
   TARANG.lib.valid.val_para.iter_glob_energy_print_start
   TARANG.lib.valid.val_para.iter_glob_energy_print_inter
   TARANG.lib.valid.val_para.iter_glob_save_buffer
   TARANG.lib.valid.val_para.iter_ekTk_save_start
   TARANG.lib.valid.val_para.iter_ekTk_save_inter
   TARANG.lib.valid.val_para.iter_ekTk_save_buffer
   TARANG.lib.valid.val_para.iter_modes_save_start
   TARANG.lib.valid.val_para.iter_modes_save_inter
   TARANG.lib.valid.val_para.iter_modes_save_buffer
   TARANG.lib.valid.val_para.VALIDATE_SOLVER


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


.. py:data:: INPUT_SET_CASE
   :value: False


.. py:data:: input_case
   :value: 'validation'


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
   :value: None


.. py:data:: output_dir
   :value: None


.. py:data:: dimension
   :value: 2


.. py:data:: Nx
   :value: 64


.. py:data:: Ny
   :value: 64


.. py:data:: Nz
   :value: 64


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
   :value: [4, 6]


.. py:data:: injection_u
   :value: 0


.. py:data:: injection_h
   :value: 0


.. py:data:: injection_plus
   :value: 0


.. py:data:: injection_minus
   :value: 0


.. py:data:: injection_vector_potential
   :value: 0


.. py:data:: injection_magnetic_helicity
   :value: 0


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
   :value: 'EULER'


.. py:data:: t_initial
   :value: 0


.. py:data:: t_final
   :value: 0.01


.. py:data:: dt
   :value: 0.001


.. py:data:: FIXED_DT
   :value: True


.. py:data:: Courant_no
   :value: 0.2


.. py:data:: t_eps
   :value: 1e-08


.. py:data:: PRINT_PARAMETERS
   :value: True


.. py:data:: RUNTIME_SAVE
   :value: False


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
   :value: 10


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
   :value: 1


.. py:data:: iter_ekTk_save_buffer
   :value: 100


.. py:data:: iter_modes_save_start
   :value: 1000


.. py:data:: iter_modes_save_inter
   :value: 1


.. py:data:: iter_modes_save_buffer
   :value: 1


.. py:data:: VALIDATE_SOLVER
   :value: True


