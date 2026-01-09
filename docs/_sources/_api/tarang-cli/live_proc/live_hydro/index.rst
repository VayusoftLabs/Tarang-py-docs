tarang-cli.live_proc.live_hydro
===============================

.. py:module:: tarang-cli.live_proc.live_hydro


Attributes
----------

.. autoapisummary::

   tarang-cli.live_proc.live_hydro.tarang_folder
   tarang-cli.live_proc.live_hydro.para_path
   tarang-cli.live_proc.live_hydro.paraIO_path
   tarang-cli.live_proc.live_hydro.spec
   tarang-cli.live_proc.live_hydro.spec
   tarang-cli.live_proc.live_hydro.vars_dict
   tarang-cli.live_proc.live_hydro.vars_dict


Functions
---------

.. autoapisummary::

   tarang-cli.live_proc.live_hydro.toggle_axis_scale
   tarang-cli.live_proc.live_hydro.live_hydro


Module Contents
---------------

.. py:data:: tarang_folder

.. py:data:: para_path

.. py:data:: paraIO_path

.. py:data:: spec
   :value: None


.. py:data:: spec
   :value: None


.. py:data:: vars_dict
   :value: None


.. py:data:: vars_dict

.. py:function:: toggle_axis_scale(event, axes)

   Toggles the axis scales (linear/log/symlog) on a click event.


.. py:function:: live_hydro(para, vars_dict)

   Live plotting for HYDRO diagnostics.

   :param para: The loaded 'para' module containing simulation parameters.
   :type para: module
   :param vars_dict: The dictionary of variable names (e.g., paraIO.Hydro_Vars).
   :type vars_dict: dict


