Latest Logs From Latest Build
==============================

Generated On: 2024-12-05 07:15:43 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/amirbhan369/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-12-05_07:13:08] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-12-05_07:13:27] STEP 2: Create topics started

  [INFO 2024-12-05_07:14:07] STEP 2: Completed

  [INFO 2024-12-05_07:14:24] STEP 3: producing data started

  [INFO 2024-12-05_07:14:31] MQTT connection established...

  [INFO 2024-12-05_07:14:32] STEP 4: Preprocessing started

  [INFO 2024-12-05_07:14:38] STEP 4: Preprocessing started

  [INFO 2024-12-05_07:14:41] STEP 7: Visualization started

  [INFO 2024-12-05_07:14:47] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-12-05_07:15:11] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2024-12-05_07:15:16] STEP 9: Starting privateGPT

  [INFO 2024-12-05_07:15:21] STEP 8: Starting docker push for: dockeramir33/projectlaragrp-10ae-amd64

  [ERROR 2024-12-05_07:15:22] STEP 8: There seems to be an issue with docker commit. Here is the command: docker commit / dockeramir33/projectlaragrp-10ae-amd64

  [INFO 2024-12-05_07:15:30] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-12-05_07:15:42] STEP 10: Started to build the documentation

  [INFO 2024-12-05_07:15:46] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


