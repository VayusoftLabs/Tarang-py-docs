tarang-cli.tarangSeq
====================

.. py:module:: tarang-cli.tarangSeq


Functions
---------

.. autoapisummary::

   tarang-cli.tarangSeq.run_main
   tarang-cli.tarangSeq.run_validation_pre
   tarang-cli.tarangSeq.run_validation_post


Module Contents
---------------

.. py:function:: run_main(para)

   Run the main solver for the specified problem kind.

   :param tarang_folder: Path to the TARANG folder.
   :type tarang_folder: str
   :param para: The parameter module containing simulation settings.
   :type para: module
   :param os: Standard Python modules for system operations.
   :type os: modules
   :param sys: Standard Python modules for system operations.
   :type sys: modules
   :param shutil: Standard Python modules for system operations.
   :type shutil: modules
   :param platform: Standard Python modules for system operations.
   :type platform: modules
   :param subprocess: Standard Python modules for system operations.
   :type subprocess: modules

   :rtype: None


.. py:function:: run_validation_pre(para, args, os)

.. py:function:: run_validation_post(para, testing_path)

