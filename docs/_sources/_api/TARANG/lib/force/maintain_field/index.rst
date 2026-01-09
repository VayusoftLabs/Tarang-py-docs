TARANG.lib.force.maintain_field
===============================

.. py:module:: TARANG.lib.force.maintain_field


Functions
---------

.. autoapisummary::

   TARANG.lib.force.maintain_field.maintain_field_mhd
   TARANG.lib.force.maintain_field.maintain_field_scalar
   TARANG.lib.force.maintain_field.maintain_field_hydro


Module Contents
---------------

.. py:function:: maintain_field_mhd(para, U, B)

.. py:function:: maintain_field_scalar(para, U, T)

   Maintain the fields for the vector and scalar fields.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField
   :param T: ScalarField object representing the scalar field.
   :type T: ScalarField

   :rtype: None


.. py:function:: maintain_field_hydro(para, U)

   Maintain the hydrodynamic field for the vector field.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField

   :rtype: None


