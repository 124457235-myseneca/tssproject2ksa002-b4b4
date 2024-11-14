Latest Logs From Latest Build
==============================

Generated On: 2024-11-14 23:17:42 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/124457235-myseneca/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-11-14_23:16:55] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-11-14_23:16:58] STEP 2: Create topics started

  [INFO 2024-11-14_23:17:09] STEP 2: Completed

  [INFO 2024-11-14_23:17:14] STEP 3: producing data started

  [INFO 2024-11-14_23:17:16] MQTT connection established...

  [INFO 2024-11-14_23:17:17] STEP 4: Preprocessing started

  [INFO 2024-11-14_23:17:19] STEP 4: Preprocessing started

  [INFO 2024-11-14_23:17:20] STEP 7: Visualization started

  [INFO 2024-11-14_23:17:25] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-11-14_23:17:30] STEP 9: Starting privateGPT

  [INFO 2024-11-14_23:17:35] STEP 8: Starting docker push for: kasunsam/tssproject2ksa002-b4b4-amd64

  [ERROR 2024-11-14_23:17:35] STEP 8: There seems to be an issue with docker commit. Here is the command: docker commit  kasunsam/tssproject2ksa002-b4b4-amd64

  [INFO 2024-11-14_23:17:41] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-11-14_23:17:42] STEP 10: Started to build the documentation

  [INFO 2024-11-14_23:17:42] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


