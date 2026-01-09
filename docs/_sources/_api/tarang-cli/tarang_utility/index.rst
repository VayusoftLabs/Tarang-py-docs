tarang-cli.tarang_utility
=========================

.. py:module:: tarang-cli.tarang_utility


Classes
-------

.. autoapisummary::

   tarang-cli.tarang_utility.TarangUtility


Module Contents
---------------

.. py:class:: TarangUtility

   .. py:method:: get_executable_path(argv_0)
      :staticmethod:



   .. py:method:: get_application_path(sys)
      :staticmethod:



   .. py:method:: print_parameters(para)
      :staticmethod:


      Print the simulation parameters for user reference.

      :param para: The parameter module containing simulation settings.
      :type para: module
      :param os: The operating system module for system-specific operations.
      :type os: module

      :rtype: None



   .. py:method:: create_output_folders(para)
      :staticmethod:



   .. py:method:: create_process_file(tarang_folder, pid)
      :staticmethod:



   .. py:method:: delete_process_file(tarang_folder, pid)
      :staticmethod:



   .. py:method:: copy_para_files(shutil, tarang_folder, para, para_folder)
      :staticmethod:



   .. py:method:: print_parameters_if_neccessary(para)
      :staticmethod:



   .. py:method:: initialize_ncp(para)
      :staticmethod:



   .. py:method:: initialize_ncp_par(para)
      :staticmethod:



   .. py:method:: clear_para(tarang_folder)
      :staticmethod:



   .. py:method:: run_live_plot(platform, subprocess, tarang_folder)
      :staticmethod:


      Launch the live plotting process for visualizing simulation data in real-time.

      :param os: The operating system module for system-specific operations.
      :type os: module
      :param platform: The platform module to detect the operating system.
      :type platform: module
      :param subprocess: The subprocess module to spawn new processes.
      :type subprocess: module
      :param tarang_folder: Path to the TARANG folder.
      :type tarang_folder: str

      :rtype: None



