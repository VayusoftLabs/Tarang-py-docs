TARANG.libp.fields.scalar_field
===============================

.. py:module:: TARANG.libp.fields.scalar_field


Attributes
----------

.. autoapisummary::

   TARANG.libp.fields.scalar_field.comm
   TARANG.libp.fields.scalar_field.rank
   TARANG.libp.fields.scalar_field.nprocs


Classes
-------

.. autoapisummary::

   TARANG.libp.fields.scalar_field.ScalarField


Module Contents
---------------

.. py:data:: comm

.. py:data:: rank

.. py:data:: nprocs

.. py:class:: ScalarField

   .. py:attribute:: fk
      :value: []



   .. py:attribute:: f
      :value: []



   .. py:attribute:: nlin
      :value: []



   .. py:attribute:: force_f
      :value: []



   .. py:attribute:: tot_energy
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



   .. py:attribute:: Tk_modes_t
      :value: []



   .. py:attribute:: Tk_mode
      :value: []



   .. py:method:: init_cond(fk, univ)


   .. py:method:: init_cond_real(f, univ)


   .. py:method:: set_arrays()


   .. py:method:: compute_total_energy()


   .. py:method:: compute_dissipation()


   .. py:method:: compute_dissipation_alter(power)


   .. py:method:: compute_ekTk(univ)


   .. py:method:: T_to_Tcopy(univ)


   .. py:method:: Tcopy_to_T(univ)


