Latest Logs From Latest Build
==============================

Generated On: 2024-12-05 03:30:40 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/124457235-myseneca/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-12-05_03:28:52] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-12-05_03:28:55] STEP 2: Create topics started

  [INFO 2024-12-05_03:29:05] STEP 2: Completed

  [INFO 2024-12-05_03:29:11] STEP 3: producing data started

  [INFO 2024-12-05_03:29:13] MQTT connection established...

  [INFO 2024-12-05_03:29:14] STEP 4: Preprocessing started

  [INFO 2024-12-05_03:29:16] STEP 4: Preprocessing started

  [INFO 2024-12-05_03:29:17] STEP 7: Visualization started

  [INFO 2024-12-05_03:29:23] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-12-05_03:29:27] STEP 9: Starting privateGPT

  [INFO 2024-12-05_03:29:33] STEP 8: Starting docker push for: kasunsam/tssproject2ksa002-b4b4-amd64

  [INFO 2024-12-05_03:29:42] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-12-05_03:29:55] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit ccdbc0e52a51 kasunsam/tssproject2ksa002-b4b4-amd64 - message=0

  [INFO 2024-12-05_03:30:32] STEP 8: Successfully ran Docker push: docker push kasunsam/tssproject2ksa002-b4b4-amd64 - message=0

  [INFO 2024-12-05_03:30:40] STEP 10: Started to build the documentation

  [INFO 2024-12-05_03:30:41] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


