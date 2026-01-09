TARANG.lib.fields.pressure
==========================

.. py:module:: TARANG.lib.fields.pressure


Classes
-------

.. autoapisummary::

   TARANG.lib.fields.pressure.Pressure


Module Contents
---------------

.. py:class:: Pressure(para)

   Class representing the pressure field for the TARANG solver.

   .. attribute:: p

      Array for the Fourier components of the pressure field.

      :type: array-like


   .. py:attribute:: para


   .. py:attribute:: p
      :value: []



   .. py:method:: set_arrays()

      Set the array for the pressure field based on the simulation parameters.



   .. py:method:: compute_pressure_u(U)

      Compute the pressure field from the nonlinear terms of the velocity field.

      :param U: VectorField object representing the velocity field.
      :type U: VectorField

      :returns: Array for the Fourier components of the pressure field.
      :rtype: array-like



