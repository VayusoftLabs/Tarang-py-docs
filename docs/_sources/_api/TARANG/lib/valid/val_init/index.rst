TARANG.lib.valid.val_init
=========================

.. py:module:: TARANG.lib.valid.val_init


Functions
---------

.. autoapisummary::

   TARANG.lib.valid.val_init.val_field_hydro
   TARANG.lib.valid.val_init.val_field_mhd
   TARANG.lib.valid.val_init.val_field_scalar


Module Contents
---------------

.. py:function:: val_field_hydro(para, U)

   Initialize the hydrodynamic field for validation.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField

   :rtype: None


.. py:function:: val_field_mhd(para, U, B)

   Initialize the magnetohydrodynamic (MHD) field for validation.

   :param B: VectorField object representing the magnetic field.
   :type B: VectorField

   :rtype: None


.. py:function:: val_field_scalar(para, U, T)

   Initialize the hydrodynamic field for validation.

   :param U: VectorField object representing the velocity field.
   :type U: VectorField

   :rtype: None


