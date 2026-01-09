TARANG.libp.valid.val_para
==========================

.. py:module:: TARANG.libp.valid.val_para


Attributes
----------

.. autoapisummary::

   TARANG.libp.valid.val_para.device
   TARANG.libp.valid.val_para.device_rank
   TARANG.libp.valid.val_para.complex_dtype
   TARANG.libp.valid.val_para.real_dtype
   TARANG.libp.valid.val_para.input_file_name
   TARANG.libp.valid.val_para.input_dir
   TARANG.libp.valid.val_para.output_dir
   TARANG.libp.valid.val_para.dimension
   TARANG.libp.valid.val_para.Nx
   TARANG.libp.valid.val_para.Ny
   TARANG.libp.valid.val_para.Nz
   TARANG.libp.valid.val_para.L
   TARANG.libp.valid.val_para.BOX_SIZE_DEFAULT
   TARANG.libp.valid.val_para.L
   TARANG.libp.valid.val_para.Rac
   TARANG.libp.valid.val_para.Ra
   TARANG.libp.valid.val_para.Pr
   TARANG.libp.valid.val_para.kappa
   TARANG.libp.valid.val_para.Omega
   TARANG.libp.valid.val_para.Nb
   TARANG.libp.valid.val_para.nu
   TARANG.libp.valid.val_para.eta
   TARANG.libp.valid.val_para.kappa
   TARANG.libp.valid.val_para.HYPO_DISSIPATION
   TARANG.libp.valid.val_para.HYPER_DISSIPATION
   TARANG.libp.valid.val_para.nu_hypo_cutoff
   TARANG.libp.valid.val_para.eta_hypo_cutoff
   TARANG.libp.valid.val_para.kappa_hypo_cutoff
   TARANG.libp.valid.val_para.nu_hypo
   TARANG.libp.valid.val_para.nu_hypo_power
   TARANG.libp.valid.val_para.nu_hyper
   TARANG.libp.valid.val_para.nu_hyper_power
   TARANG.libp.valid.val_para.eta_hypo
   TARANG.libp.valid.val_para.eta_hypo_power
   TARANG.libp.valid.val_para.eta_hyper
   TARANG.libp.valid.val_para.eta_hyper_power
   TARANG.libp.valid.val_para.kappa_hypo
   TARANG.libp.valid.val_para.kappa_hypo_power
   TARANG.libp.valid.val_para.kappa_hyper
   TARANG.libp.valid.val_para.kappa_hyper_power
   TARANG.libp.valid.val_para.FORCING_ENABLED
   TARANG.libp.valid.val_para.forcing_range
   TARANG.libp.valid.val_para.injection_rate
   TARANG.libp.valid.val_para.injection_e_plus
   TARANG.libp.valid.val_para.injection_e_minus
   TARANG.libp.valid.val_para.injection_e_r
   TARANG.libp.valid.val_para.ROTATION_ENABLED
   TARANG.libp.valid.val_para.MAINTAIN_FIELD
   TARANG.libp.valid.val_para.maintain_mux
   TARANG.libp.valid.val_para.t_initial
   TARANG.libp.valid.val_para.t_final
   TARANG.libp.valid.val_para.dt
   TARANG.libp.valid.val_para.t_eps
   TARANG.libp.valid.val_para.modes_save
   TARANG.libp.valid.val_para.PRINT_PARAMETERS
   TARANG.libp.valid.val_para.GPU_DIRECT_STORAGE
   TARANG.libp.valid.val_para.USE_BINDING
   TARANG.libp.valid.val_para.PLANAR_SPECTRA
   TARANG.libp.valid.val_para.SAVE_VORTICITY
   TARANG.libp.valid.val_para.SAVE_VECPOT
   TARANG.libp.valid.val_para.iter_field_save_start
   TARANG.libp.valid.val_para.iter_field_save_inter
   TARANG.libp.valid.val_para.iter_glob_energy_print_start
   TARANG.libp.valid.val_para.iter_glob_energy_print_inter
   TARANG.libp.valid.val_para.iter_ekTk_save_start
   TARANG.libp.valid.val_para.iter_ekTk_save_inter
   TARANG.libp.valid.val_para.iter_modes_save_start
   TARANG.libp.valid.val_para.iter_modes_save_inter
   TARANG.libp.valid.val_para.VALIDATE_SOLVER


Module Contents
---------------

.. py:data:: device
   :value: 'GPU'


.. py:data:: device_rank
   :value: 0


.. py:data:: complex_dtype
   :value: 'complex'


.. py:data:: real_dtype
   :value: 'float64'


.. py:data:: input_file_name
   :value: 'init_cond.h5'


.. py:data:: input_dir
   :value: 'input/'


.. py:data:: output_dir
   :value: 'TARANG/libp/valid/output/'


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

.. py:data:: Omega
   :value: 0


.. py:data:: Nb
   :value: 0


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


.. py:data:: nu_hypo_cutoff
   :value: -1


.. py:data:: eta_hypo_cutoff
   :value: -1


.. py:data:: kappa_hypo_cutoff
   :value: -1


.. py:data:: nu_hypo
   :value: 1


.. py:data:: nu_hypo_power
   :value: -2


.. py:data:: nu_hyper
   :value: 0.0001


.. py:data:: nu_hyper_power
   :value: 2


.. py:data:: eta_hypo
   :value: 1


.. py:data:: eta_hypo_power
   :value: -2


.. py:data:: eta_hyper
   :value: 0.0001


.. py:data:: eta_hyper_power
   :value: 2


.. py:data:: kappa_hypo
   :value: 1


.. py:data:: kappa_hypo_power
   :value: -2


.. py:data:: kappa_hyper
   :value: 0.0001


.. py:data:: kappa_hyper_power
   :value: 2


.. py:data:: FORCING_ENABLED
   :value: False


.. py:data:: forcing_range
   :value: [4, 6]


.. py:data:: injection_rate
   :value: 0


.. py:data:: injection_e_plus
   :value: 1


.. py:data:: injection_e_minus
   :value: 1


.. py:data:: injection_e_r
   :value: 1


.. py:data:: ROTATION_ENABLED
   :value: False


.. py:data:: MAINTAIN_FIELD
   :value: False


.. py:data:: maintain_mux
   :value: 1


.. py:data:: t_initial
   :value: 0


.. py:data:: t_final
   :value: 0.01


.. py:data:: dt
   :value: 0.001


.. py:data:: t_eps
   :value: 1e-08


.. py:data:: modes_save
   :value: []


.. py:data:: PRINT_PARAMETERS
   :value: True


.. py:data:: GPU_DIRECT_STORAGE
   :value: False


.. py:data:: USE_BINDING
   :value: True


.. py:data:: PLANAR_SPECTRA
   :value: False


.. py:data:: SAVE_VORTICITY
   :value: False


.. py:data:: SAVE_VECPOT
   :value: False


.. py:data:: iter_field_save_start
   :value: 0


.. py:data:: iter_field_save_inter
   :value: 10


.. py:data:: iter_glob_energy_print_start
   :value: 0


.. py:data:: iter_glob_energy_print_inter
   :value: 1


.. py:data:: iter_ekTk_save_start
   :value: 0


.. py:data:: iter_ekTk_save_inter
   :value: 1


.. py:data:: iter_modes_save_start
   :value: 1000


.. py:data:: iter_modes_save_inter
   :value: 1


.. py:data:: VALIDATE_SOLVER
   :value: True


