TARANG.lib.force.compute_force_scalar
=====================================

.. py:module:: TARANG.lib.force.compute_force_scalar


Functions
---------

.. autoapisummary::

   TARANG.lib.force.compute_force_scalar.compute_force_scalar
   TARANG.lib.force.compute_force_scalar.compute_random_forcing
   TARANG.lib.force.compute_force_scalar.compute_rotation
   TARANG.lib.force.compute_force_scalar.compute_buoyancy
   TARANG.lib.force.compute_force_scalar.craya_to_cartesian


Module Contents
---------------

.. py:function:: compute_force_scalar(para, U, T, univ)

   Compute the scalar force for the vector and scalar fields.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param T: ScalarField object representing the scalar field.
   :type T: ScalarField
   :param univ: UniversalArrays object for temporary storage.
   :type univ: UniversalArrays

   :rtype: None


.. py:function:: compute_random_forcing(para, U, T, univ)

.. py:function:: compute_rotation(para, U)

   Compute the rotational force for the vector field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField

   :rtype: None


.. py:function:: compute_buoyancy(para, U, T)

   Compute the buoyancy force for the vector and scalar fields.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param T: ScalarField object representing the scalar field.
   :type T: ScalarField

   :rtype: None


.. py:function:: craya_to_cartesian(u1, Vkx, Vkz, k_mag, i, j)

