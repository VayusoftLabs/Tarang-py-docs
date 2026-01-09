tarang-cli.tarang_aws
=====================

.. py:module:: tarang-cli.tarang_aws


Attributes
----------

.. autoapisummary::

   tarang-cli.tarang_aws.WORKER_START_TIME
   tarang-cli.tarang_aws.logger
   tarang-cli.tarang_aws.BUCKET_NAME
   tarang-cli.tarang_aws.REGION
   tarang-cli.tarang_aws.POLL_INTERVAL
   tarang-cli.tarang_aws.LOCAL_WORK_DIR


Functions
---------

.. autoapisummary::

   tarang-cli.tarang_aws.get_s3_client
   tarang-cli.tarang_aws.list_pending_jobs
   tarang-cli.tarang_aws.update_job_status
   tarang-cli.tarang_aws.run_s3_job
   tarang-cli.tarang_aws.run_local_cli
   tarang-cli.tarang_aws.main


Module Contents
---------------

.. py:data:: WORKER_START_TIME

.. py:data:: logger

.. py:data:: BUCKET_NAME

.. py:data:: REGION

.. py:data:: POLL_INTERVAL
   :value: 60


.. py:data:: LOCAL_WORK_DIR

.. py:function:: get_s3_client()

   Initialize S3 client


.. py:function:: list_pending_jobs(s3)

   List all para.py files in users/*/input/ that don't have a corresponding status


.. py:function:: update_job_status(s3, username, job_id, status, message='', progress=0)

   Update job status in S3


.. py:function:: run_s3_job(job)

   Run a single simulation job from S3


.. py:function:: run_local_cli()

.. py:function:: main()

