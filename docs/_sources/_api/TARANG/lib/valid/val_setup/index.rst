TARANG.lib.valid.val_setup
==========================

.. py:module:: TARANG.lib.valid.val_setup


Functions
---------

.. autoapisummary::

   TARANG.lib.valid.val_setup.preprocessing
   TARANG.lib.valid.val_setup.module_load
   TARANG.lib.valid.val_setup.validator
   TARANG.lib.valid.val_setup.h5_read
   TARANG.lib.valid.val_setup.cleanup


Module Contents
---------------

.. py:function:: preprocessing(args, para)

   Preprocess the parameter file for validation.

   :param args: List of arguments specifying the validation setup.
   :type args: list

   :rtype: None


.. py:function:: module_load(para)

   Load the testing module based on the parameters.

   :returns: Path to the testing module.
   :rtype: str


.. py:function:: validator(testing_path, para)

   Validate the global parameters against the testing module.

   :param testing_path: Path to the testing module.
   :type testing_path: str

   :rtype: None


.. py:function:: h5_read(filename, dataset, para)

   Read data from an HDF5 file.

   :param filename: Path to the HDF5 file.
   :type filename: str
   :param dataset: Name of the dataset to read.
   :type dataset: str

   :returns: Data read from the HDF5 file.
   :rtype: array-like


.. py:function:: cleanup(para)

   Clean up the validation setup by removing temporary files.

   :rtype: None


