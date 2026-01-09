TARANG.libp.fields.vect_field
=============================

.. py:module:: TARANG.libp.fields.vect_field


Attributes
----------

.. autoapisummary::

   TARANG.libp.fields.vect_field.comm
   TARANG.libp.fields.vect_field.rank
   TARANG.libp.fields.vect_field.nprocs


Classes
-------

.. autoapisummary::

   TARANG.libp.fields.vect_field.VectorField


Module Contents
---------------

.. py:data:: comm

.. py:data:: rank

.. py:data:: nprocs

.. py:class:: VectorField

   .. py:attribute:: Vkx
      :value: []



   .. py:attribute:: Vky
      :value: []



   .. py:attribute:: Vkz
      :value: []



   .. py:attribute:: Vx
      :value: []



   .. py:attribute:: Vy
      :value: []



   .. py:attribute:: Vz
      :value: []



   .. py:attribute:: force_Vx
      :value: []



   .. py:attribute:: force_Vy
      :value: []



   .. py:attribute:: force_Vz
      :value: []



   .. py:attribute:: nlinx
      :value: []



   .. py:attribute:: nliny
      :value: []



   .. py:attribute:: nlinz
      :value: []



   .. py:attribute:: ek
      :value: []



   .. py:attribute:: Tk
      :value: []



   .. py:attribute:: ek_table
      :value: []



   .. py:attribute:: Tk_table
      :value: []



   .. py:attribute:: total_energy
      :value: []



   .. py:attribute:: total_dissipation
      :value: []



   .. py:attribute:: standard_dissipation
      :value: []



   .. py:attribute:: divergence
      :value: []



   .. py:attribute:: total_injection
      :value: []



   .. py:attribute:: ur
      :value: []



   .. py:attribute:: Vkx_modes_t
      :value: []



   .. py:attribute:: Vky_modes_t
      :value: []



   .. py:attribute:: Vkz_modes_t
      :value: []



   .. py:attribute:: Vkx_mode
      :value: []



   .. py:attribute:: Vkz_mode
      :value: []



   .. py:attribute:: Vky_mode
      :value: []



   .. py:method:: set_arrays()


   .. py:method:: init_cond(Vkx, Vky, Vkz, univ)


   .. py:method:: init_cond_real(Vx, Vy, Vz, univ)


   .. py:method:: update2D_Vkz(kx, kz)


   .. py:method:: update3D_Vkz(kx, ky, kz)


   .. py:method:: compute_divergence()


   .. py:method:: compute_total_energy()


   .. py:method:: compute_total_injection()


   .. py:method:: compute_dissipation()


   .. py:method:: compute_dissipation_alter(power)


   .. py:method:: compute_ekTk(univ)


   .. py:method:: dot_prod_nlin_VF(W=PlainVectorField())


   .. py:method:: fill_shell(inner_radius, outer_radius, W=PlainVectorField())


   .. py:method:: U_to_Ucopy(univ)


   .. py:method:: Ucopy_to_U(univ)


   .. py:method:: B_to_Bcopy(univ)


   .. py:method:: Bcopy_to_B(univ)


