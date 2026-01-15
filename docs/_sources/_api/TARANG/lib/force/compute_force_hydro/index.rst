TARANG.lib.force.compute_force_hydro
====================================

.. py:module:: TARANG.lib.force.compute_force_hydro


Functions
---------

.. autoapisummary::

   TARANG.lib.force.compute_force_hydro.compute_force_hydro
   TARANG.lib.force.compute_force_hydro.compute_random_forcing
   TARANG.lib.force.compute_force_hydro.compute_carati_forcing
   TARANG.lib.force.compute_force_hydro.compute_random_forcing_old
   TARANG.lib.force.compute_force_hydro.compute_rotation
   TARANG.lib.force.compute_force_hydro.craya_to_cartesian
   TARANG.lib.force.compute_force_hydro.craya_to_cartesian_old
   TARANG.lib.force.compute_force_hydro.compute_taylor_green_forcing
   TARANG.lib.force.compute_force_hydro.compute_toner_tu_forcing


Module Contents
---------------

.. py:function:: compute_force_hydro(para, U, univ)

   Compute the hydrodynamic force for the vector field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: compute_random_forcing(para, U, univ)

.. py:function:: compute_carati_forcing(para, U)

.. py:function:: compute_random_forcing_old(para, U, univ)

.. py:function:: compute_rotation(para, U)

   Compute the rotational force for the vector field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField

   :rtype: None


.. py:function:: craya_to_cartesian(u1, Vkx, Vkz, k_mag, i, j)

.. py:function:: craya_to_cartesian_old(u1, Vkx, Vkz, k_mag, i, j)

.. py:function:: compute_taylor_green_forcing(para, U)

   Computes spectral forcing for Taylor-Green vortex.

   3D Forcing: F = F0 * [sin(x)cos(y)cos(z), -cos(x)sin(y)cos(z), 0]
   2D Forcing: F = F0 * [sin(x)cos(y), -cos(x)sin(y)]


.. py:function:: compute_toner_tu_forcing(para, U, univ)

   Computes Toner-Tu active matter forcing (Local / "Actual" term).

   Equation (Real Space):
       F = (alpha - beta * |v|^2) * v

   This requires computing the cubic nonlinearity in real space
   and transforming it to spectral space.


