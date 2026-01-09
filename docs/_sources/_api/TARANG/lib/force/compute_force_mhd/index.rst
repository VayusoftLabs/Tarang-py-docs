TARANG.lib.force.compute_force_mhd
==================================

.. py:module:: TARANG.lib.force.compute_force_mhd


Functions
---------

.. autoapisummary::

   TARANG.lib.force.compute_force_mhd.compute_force_mhd
   TARANG.lib.force.compute_force_mhd.compute_carati_forcing
   TARANG.lib.force.compute_force_mhd.compute_random_forcing
   TARANG.lib.force.compute_force_mhd.compute_random_forcing_old
   TARANG.lib.force.compute_force_mhd.craya_to_cartesian


Module Contents
---------------

.. py:function:: compute_force_mhd(para, U, B, univ)

   Compute the magnetohydrodynamic (MHD) force for the vector fields.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param B: VectorField object representing the magnetic field.
   :type B: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: compute_carati_forcing(para, U, B)

.. py:function:: compute_random_forcing(para, U, B, univ)

.. py:function:: compute_random_forcing_old(para, U, B, univ)

.. py:function:: craya_to_cartesian(u1, Vkx, Vkz, k_mag, i, j)

