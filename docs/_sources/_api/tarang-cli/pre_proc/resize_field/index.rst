tarang-cli.pre_proc.resize_field
================================

.. py:module:: tarang-cli.pre_proc.resize_field


Attributes
----------

.. autoapisummary::

   tarang-cli.pre_proc.resize_field.in_name
   tarang-cli.pre_proc.resize_field.out_name
   tarang-cli.pre_proc.resize_field.kind
   tarang-cli.pre_proc.resize_field.elsasser_switch
   tarang-cli.pre_proc.resize_field.Nx
   tarang-cli.pre_proc.resize_field.Ny
   tarang-cli.pre_proc.resize_field.Nz
   tarang-cli.pre_proc.resize_field.a1
   tarang-cli.pre_proc.resize_field.a2
   tarang-cli.pre_proc.resize_field.a3
   tarang-cli.pre_proc.resize_field.b1
   tarang-cli.pre_proc.resize_field.b2
   tarang-cli.pre_proc.resize_field.b3
   tarang-cli.pre_proc.resize_field.theta
   tarang-cli.pre_proc.resize_field.a1


Functions
---------

.. autoapisummary::

   tarang-cli.pre_proc.resize_field.resize
   tarang-cli.pre_proc.resize_field.custom
   tarang-cli.pre_proc.resize_field.hydro
   tarang-cli.pre_proc.resize_field.mhd
   tarang-cli.pre_proc.resize_field.scalar
   tarang-cli.pre_proc.resize_field.main


Module Contents
---------------

.. py:data:: in_name
   :value: 'in.h5'


.. py:data:: out_name
   :value: 'out.h5'


.. py:data:: kind
   :value: 'hydro'


.. py:data:: elsasser_switch
   :value: False


.. py:data:: Nx
   :value: 4


.. py:data:: Ny
   :value: 4


.. py:data:: Nz
   :value: 4


.. py:data:: a1
   :value: 'Vkx'


.. py:data:: a2
   :value: 'Vkz'


.. py:data:: a3
   :value: 'Vky'


.. py:data:: b1
   :value: 'Bkx'


.. py:data:: b2
   :value: 'Bkz'


.. py:data:: b3
   :value: 'Bky'


.. py:data:: theta
   :value: 'T'


.. py:data:: a1
   :value: 'zpkx'


.. py:function:: resize(Ak, Ak_in, N)

.. py:function:: custom()

.. py:function:: hydro()

.. py:function:: mhd()

.. py:function:: scalar()

.. py:function:: main()

