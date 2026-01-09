TARANG.libp.global_fns.spectral_setup
=====================================

.. py:module:: TARANG.libp.global_fns.spectral_setup


Attributes
----------

.. autoapisummary::

   TARANG.libp.global_fns.spectral_setup.comm
   TARANG.libp.global_fns.spectral_setup.rank
   TARANG.libp.global_fns.spectral_setup.nprocs
   TARANG.libp.global_fns.spectral_setup.kx
   TARANG.libp.global_fns.spectral_setup.ky
   TARANG.libp.global_fns.spectral_setup.kz
   TARANG.libp.global_fns.spectral_setup.kfactor
   TARANG.libp.global_fns.spectral_setup.Ngrid
   TARANG.libp.global_fns.spectral_setup.Ngrid
   TARANG.libp.global_fns.spectral_setup.Ngrid
   TARANG.libp.global_fns.spectral_setup.dealiasing_index
   TARANG.libp.global_fns.spectral_setup.k_max
   TARANG.libp.global_fns.spectral_setup.min_radius_outside
   TARANG.libp.global_fns.spectral_setup.k_min
   TARANG.libp.global_fns.spectral_setup.k_array


Functions
---------

.. autoapisummary::

   TARANG.libp.global_fns.spectral_setup.getSplit
   TARANG.libp.global_fns.spectral_setup.redistribute
   TARANG.libp.global_fns.spectral_setup.xderiv
   TARANG.libp.global_fns.spectral_setup.yderiv
   TARANG.libp.global_fns.spectral_setup.zderiv
   TARANG.libp.global_fns.spectral_setup.forward_transform
   TARANG.libp.global_fns.spectral_setup.inverse_transform
   TARANG.libp.global_fns.spectral_setup.dealias
   TARANG.libp.global_fns.spectral_setup.reality_cond
   TARANG.libp.global_fns.spectral_setup.generate_spectrum2D
   TARANG.libp.global_fns.spectral_setup.generate_spectrum3D
   TARANG.libp.global_fns.spectral_setup.boundary_sin_cond
   TARANG.libp.global_fns.spectral_setup.boundary_cos_cond
   TARANG.libp.global_fns.spectral_setup.craya_to_cartesian
   TARANG.libp.global_fns.spectral_setup.compute_phi


Module Contents
---------------

.. py:data:: comm

.. py:data:: rank

.. py:data:: nprocs

.. py:function:: getSplit(lendim, P)

   Function to return the split indices, and block sizes when a dimension of length lendim is
   divided into P blocks. (P need not divide lendim)
   --
   :param lendim: Length of the dimension to be split (integer)
   :param P: Number of parts for the dimension to be broken into

   :returns: a list of length P containing (start index, block size, end index) of all blocks
   :rtype: split

   .. rubric:: Examples

   - getSplit(4, 4) returns [(0, 1, 1), (1, 1, 2), (2, 1, 3), (3, 1, 4)]
   - getSplit(6, 4) returns [(0, 2, 2), (2, 2, 4), (4, 1, 5), (5, 1, 6)]

   Note: Not tested when P > lendim


.. py:function:: redistribute(APre, APost, axisPre, axisPost, comm)

   Function to redistribute numpy array (almost) equally
   among all nodes. Array is initally distributed along axisPre and
   this function returns the array redistributed along axisPost.
   --
   :param APre: The array to redistribute (initially distributed along axisPre)
   :param axisPre: The axis along which array is distributed (default 0)
   :param axisPost: The axis along which array is to be redistributed (default 1).
   :param comm: MPI Communicator object (default MPI.COMM_WORLD)

   :returns: Redistributed array (distributed along axisPost)
   :rtype: APost

   .. rubric:: Examples

   - if axisPre is 0, axisPost = 1, comm.Get_size() is 3,
      and initially arrays have shapes
      [2, 8, 6], [2, 8, 6], [1, 8, 6], then
      redistributed arrays will have shapes
      [5, 3, 6], [5, 3, 6], [5, 2, 6]

   Note: Not tested when comm.Get_size() > Apre.shape[axisPost]


.. py:data:: kx

.. py:data:: ky

.. py:data:: kz

.. py:data:: kfactor

.. py:data:: Ngrid

.. py:data:: Ngrid

.. py:data:: Ngrid

.. py:data:: dealiasing_index

.. py:data:: k_max

.. py:data:: min_radius_outside

.. py:data:: k_min

.. py:data:: k_array

.. py:function:: xderiv(Ak)

.. py:function:: yderiv(Ak)

.. py:function:: zderiv(Ak)

.. py:function:: forward_transform(A, Ak)

.. py:function:: inverse_transform(Ak, A, temp)

.. py:function:: dealias(Ak)

.. py:function:: reality_cond(Ak, temp_xy)

.. py:function:: generate_spectrum2D(Ak, ek, Tk, nlin, temp)

.. py:function:: generate_spectrum3D(Ak, ek, Tk, nlin, temp)

.. py:function:: boundary_sin_cond(Ak)

.. py:function:: boundary_cos_cond(Ak)

.. py:function:: craya_to_cartesian(u1, Vkx, Vkz, k_mag, i, j)

.. py:function:: compute_phi(i, j)

