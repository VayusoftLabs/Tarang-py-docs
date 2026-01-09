TARANG.lib.global_fns.spectral_setup
====================================

.. py:module:: TARANG.lib.global_fns.spectral_setup


Attributes
----------

.. autoapisummary::

   TARANG.lib.global_fns.spectral_setup.kx
   TARANG.lib.global_fns.spectral_setup.ky
   TARANG.lib.global_fns.spectral_setup.kz
   TARANG.lib.global_fns.spectral_setup.kfactor
   TARANG.lib.global_fns.spectral_setup.Ngrid
   TARANG.lib.global_fns.spectral_setup.NgridF
   TARANG.lib.global_fns.spectral_setup.kfactor
   TARANG.lib.global_fns.spectral_setup.kx_mesh
   TARANG.lib.global_fns.spectral_setup.ky_mesh
   TARANG.lib.global_fns.spectral_setup.NgridF
   TARANG.lib.global_fns.spectral_setup.kz_mesh
   TARANG.lib.global_fns.spectral_setup.ksqr
   TARANG.lib.global_fns.spectral_setup.dealiasing_index
   TARANG.lib.global_fns.spectral_setup.min_radius_outside
   TARANG.lib.global_fns.spectral_setup.k_array


Functions
---------

.. autoapisummary::

   TARANG.lib.global_fns.spectral_setup.SpectralInit
   TARANG.lib.global_fns.spectral_setup.xderiv
   TARANG.lib.global_fns.spectral_setup.yderiv
   TARANG.lib.global_fns.spectral_setup.zderiv
   TARANG.lib.global_fns.spectral_setup.forward_transform
   TARANG.lib.global_fns.spectral_setup.inverse_transform
   TARANG.lib.global_fns.spectral_setup.dealias
   TARANG.lib.global_fns.spectral_setup.dealias_old
   TARANG.lib.global_fns.spectral_setup.reality_cond
   TARANG.lib.global_fns.spectral_setup.generate_spectrum2D
   TARANG.lib.global_fns.spectral_setup.generate_spectrum3D
   TARANG.lib.global_fns.spectral_setup.generate_specta_planar
   TARANG.lib.global_fns.spectral_setup.resize
   TARANG.lib.global_fns.spectral_setup.boundary_sin_cond
   TARANG.lib.global_fns.spectral_setup.boundary_cos_cond


Module Contents
---------------

.. py:data:: kx
   :value: None


.. py:data:: ky
   :value: None


.. py:data:: kz
   :value: None


.. py:data:: kfactor
   :value: None


.. py:data:: Ngrid
   :value: None


.. py:data:: NgridF
   :value: None


.. py:data:: kfactor
   :value: None


.. py:data:: kx_mesh
   :value: None


.. py:data:: ky_mesh
   :value: None


.. py:data:: NgridF
   :value: None


.. py:data:: kz_mesh
   :value: None


.. py:data:: ksqr
   :value: None


.. py:data:: dealiasing_index
   :value: None


.. py:data:: min_radius_outside
   :value: None


.. py:data:: k_array
   :value: None


.. py:function:: SpectralInit(para)

.. py:function:: xderiv(Ak)

   Compute the x-derivative of the array in Fourier space.

   :param Ak: Array in Fourier space.
   :type Ak: array-like

   :returns: x-derivative of the array in Fourier space.
   :rtype: array-like


.. py:function:: yderiv(Ak)

   Compute the y-derivative of the array in Fourier space.

   :param Ak: Array in Fourier space.
   :type Ak: array-like

   :returns: y-derivative of the array in Fourier space.
   :rtype: array-like


.. py:function:: zderiv(Ak)

   Compute the z-derivative of the array in Fourier space.

   :param Ak: Array in Fourier space.
   :type Ak: array-like

   :returns: z-derivative of the array in Fourier space.
   :rtype: array-like


.. py:function:: forward_transform(para, A, Ak)

   Compute the forward Fourier transform of the array.

   :param A: Array in real space.
   :type A: array-like
   :param Ak: Array in Fourier space.
   :type Ak: array-like

   :returns: Forward Fourier transform of the array.
   :rtype: array-like


.. py:function:: inverse_transform(para, Ak, A)

   Compute the inverse Fourier transform of the array.

   :param Ak: Array in Fourier space.
   :type Ak: array-like
   :param A: Array in real space.
   :type A: array-like

   :returns: Inverse Fourier transform of the array.
   :rtype: array-like


.. py:function:: dealias(Ak)

   Apply dealiasing to the array in Fourier space.

   :param Ak: Array in Fourier space.
   :type Ak: array-like

   :returns: Dealiased array in Fourier space.
   :rtype: array-like


.. py:function:: dealias_old(para, Ak)

   Apply old dealiasing method to the array in Fourier space.

   :param Ak: Array in Fourier space.
   :type Ak: array-like

   :returns: Dealiased array in Fourier space.
   :rtype: array-like


.. py:function:: reality_cond(para, Ak)

   Apply reality condition to the array in Fourier space.

   :param Ak: Array in Fourier space.
   :type Ak: array-like

   :returns: Array in Fourier space with reality condition applied.
   :rtype: array-like


.. py:function:: generate_spectrum2D(para, Ak, ek, Tk, nlin, temp)

   Generate the 2D energy spectrum and transfer function.

   :param Ak: Array in Fourier space.
   :type Ak: array-like
   :param ek: Array for the energy spectrum.
   :type ek: array-like
   :param Tk: Array for the transfer function.
   :type Tk: array-like
   :param nlin: Array for the nonlinear terms.
   :type nlin: array-like
   :param temp: Temporary array for calculations.
   :type temp: array-like

   :rtype: None


.. py:function:: generate_spectrum3D(para, Ak, ek, Tk, nlin, temp)

   Generate the 3D energy spectrum and transfer function.

   :param Ak: Array in Fourier space.
   :type Ak: array-like
   :param ek: Array for the energy spectrum.
   :type ek: array-like
   :param Tk: Array for the transfer function.
   :type Tk: array-like
   :param nlin: Array for the nonlinear terms.
   :type nlin: array-like
   :param temp: Temporary array for calculations.
   :type temp: array-like

   :rtype: None


.. py:function:: generate_specta_planar(para, Ak, ek, Tk, nlin, temp)

   Generate the planar energy spectrum and transfer function.

   :param Ak: Array in Fourier space.
   :type Ak: array-like
   :param ek: Array for the energy spectrum.
   :type ek: array-like
   :param Tk: Array for the transfer function.
   :type Tk: array-like
   :param nlin: Array for the nonlinear terms.
   :type nlin: array-like
   :param temp: Temporary array for calculations.
   :type temp: array-like

   :rtype: None


.. py:function:: resize(Ak_in, Ak, N)

   Resize the array `Ak_in` to fit into the array `Ak` with the given dimensions `N`.

   :param Ak: Array to be resized.
   :type Ak: array-like
   :param Ak_in: Input array to be resized.
   :type Ak_in: array-like
   :param N: Dimensions of the output array.
   :type N: list of int

   :returns: Resized array.
   :rtype: array-like


.. py:function:: boundary_sin_cond(para, Ak)

   Apply sine boundary condition to the array in Fourier space.

   :param Ak: Array in Fourier space.
   :type Ak: array-like

   :returns: Array in Fourier space with sine boundary condition applied.
   :rtype: array-like


.. py:function:: boundary_cos_cond(para, Ak)

   Apply cosine boundary condition to the array in Fourier space.

   :param Ak: Array in Fourier space.
   :type Ak: array-like

   :returns: Array in Fourier space with cosine boundary condition applied.
   :rtype: array-like


