# covid-2-classifier

Step 1

Clone this repostory or download zip file Code -> Download Zip


Step 2 

Extract zip file covid-2-classifier-main.zip


Step 3 Open Folder in SARS-Cov-2 in PyCharm

Step 4

Extract SARS-Cov-2\downloadfile\largedataset.rar file
After extract move folder from \SARS-Cov-2\downloadfile\largedataset\largedataset to SARS-Cov-2\largedataset

 
Step 5

follow the instruction in  \SARS-Cov-2\install.doc
make sure packages are install in python: 'scikit-learn','tensorflow==2.5.0','bio','pandas','matplotlib','seaborn'


Step 6

Run \SARS-Cov-2\largedatasetMainTrainTest.py in pyCharm

Output:

D:\ganesh\me\project\covid-19\clone_test\SARS-Cov-2\venv\Scripts\python.exe D:/ganesh/me/project/covid-19/clone_test/SARS-Cov-2/largedatasetMainTrainTest.py
2021-07-25 11:28:18.474282: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cudart64_110.dll'; dlerror: cudart64_110.dll not found
2021-07-25 11:28:18.507064: I tensorflow/stream_executor/cuda/cudart_stub.cc:29] Ignore above cudart dlerror if you do not have a GPU set up on your machine.
2021-07-25 11:28:43.892699: I tensorflow/stream_executor/platform/default/dso_loader.cc:53] Successfully opened dynamic library nvcuda.dll
2021-07-25 11:28:45.267500: I tensorflow/core/common_runtime/gpu/gpu_device.cc:1733] Found device 0 with properties: 
pciBusID: 0000:01:00.0 name: GeForce GTX 1650 computeCapability: 7.5
coreClock: 1.56GHz coreCount: 16 deviceMemorySize: 4.00GiB deviceMemoryBandwidth: 119.24GiB/s
2021-07-25 11:28:45.282430: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cudart64_110.dll'; dlerror: cudart64_110.dll not found
2021-07-25 11:28:45.287969: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cublas64_11.dll'; dlerror: cublas64_11.dll not found
2021-07-25 11:28:45.292786: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cublasLt64_11.dll'; dlerror: cublasLt64_11.dll not found
2021-07-25 11:28:45.297896: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cufft64_10.dll'; dlerror: cufft64_10.dll not found
2021-07-25 11:28:45.302419: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'curand64_10.dll'; dlerror: curand64_10.dll not found
2021-07-25 11:28:45.306710: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cusolver64_11.dll'; dlerror: cusolver64_11.dll not found
2021-07-25 11:28:45.311727: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cusparse64_11.dll'; dlerror: cusparse64_11.dll not found
2021-07-25 11:28:45.314250: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cudnn64_8.dll'; dlerror: cudnn64_8.dll not found
2021-07-25 11:28:45.314691: W tensorflow/core/common_runtime/gpu/gpu_device.cc:1766] Cannot dlopen some GPU libraries. Please make sure the missing libraries mentioned above are installed properly if you would like to use GPU. Follow the guide at https://www.tensorflow.org/install/gpu for how to download and setup the required libraries for your platform.
Skipping registering GPU devices...
2021-07-25 11:28:45.544738: I tensorflow/core/platform/cpu_feature_guard.cc:142] This TensorFlow binary is optimized with oneAPI Deep Neural Network Library (oneDNN) to use the following CPU instructions in performance-critical operations:  AVX AVX2
To enable them in other operations, rebuild TensorFlow with the appropriate compiler flags.
2021-07-25 11:28:45.573658: I tensorflow/core/common_runtime/gpu/gpu_device.cc:1258] Device interconnect StreamExecutor with strength 1 edge matrix:
2021-07-25 11:28:45.574727: I tensorflow/core/common_runtime/gpu/gpu_device.cc:1264]      
Dictionory Size:  232
2021-07-25 11:28:50.332718: I tensorflow/compiler/mlir/mlir_graph_optimization_pass.cc:176] None of the MLIR Optimization Passes are enabled (registered 2)
Epoch 1/10
79/79 [==============================] - 42s 177ms/step - loss: 0.1822 - accuracy: 0.8978
Epoch 2/10
79/79 [==============================] - 14s 181ms/step - loss: 0.0434 - accuracy: 0.9496
Epoch 3/10
79/79 [==============================] - 13s 169ms/step - loss: 0.0341 - accuracy: 0.9483
Epoch 4/10
79/79 [==============================] - 14s 173ms/step - loss: 0.0309 - accuracy: 0.9531
Epoch 5/10
79/79 [==============================] - 13s 170ms/step - loss: 0.0280 - accuracy: 0.9499
Epoch 6/10
79/79 [==============================] - 15s 186ms/step - loss: 0.0246 - accuracy: 0.9611
Epoch 7/10
79/79 [==============================] - 14s 182ms/step - loss: 0.0228 - accuracy: 0.9749
Epoch 8/10
79/79 [==============================] - 15s 187ms/step - loss: 0.0193 - accuracy: 0.9812
Epoch 9/10
79/79 [==============================] - 14s 181ms/step - loss: 0.0176 - accuracy: 0.9880
Epoch 10/10
79/79 [==============================] - 14s 173ms/step - loss: 0.0136 - accuracy: 0.9954
[0.0027127964422106743, 0.9990933537483215]
loss: 0.27%
accuracy: 99.91%

Process finished with exit code 0




Step 7

Run \SARS-Cov-2\largedatasetMainTestExample.py in pyCharm

output :
D:\ganesh\me\project\covid-19\clone_test\SARS-Cov-2\venv\Scripts\python.exe D:/ganesh/me/project/covid-19/clone_test/SARS-Cov-2/largedatasetMainTestExample.py
2021-07-25 11:33:46.869633: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cudart64_110.dll'; dlerror: cudart64_110.dll not found
2021-07-25 11:33:46.869982: I tensorflow/stream_executor/cuda/cudart_stub.cc:29] Ignore above cudart dlerror if you do not have a GPU set up on your machine.
2021-07-25 11:33:48.623785: I tensorflow/stream_executor/platform/default/dso_loader.cc:53] Successfully opened dynamic library nvcuda.dll
2021-07-25 11:33:49.564728: I tensorflow/core/common_runtime/gpu/gpu_device.cc:1733] Found device 0 with properties: 
pciBusID: 0000:01:00.0 name: GeForce GTX 1650 computeCapability: 7.5
coreClock: 1.56GHz coreCount: 16 deviceMemorySize: 4.00GiB deviceMemoryBandwidth: 119.24GiB/s
2021-07-25 11:33:49.565905: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cudart64_110.dll'; dlerror: cudart64_110.dll not found
2021-07-25 11:33:49.566904: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cublas64_11.dll'; dlerror: cublas64_11.dll not found
2021-07-25 11:33:49.567879: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cublasLt64_11.dll'; dlerror: cublasLt64_11.dll not found
2021-07-25 11:33:49.568861: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cufft64_10.dll'; dlerror: cufft64_10.dll not found
2021-07-25 11:33:49.569829: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'curand64_10.dll'; dlerror: curand64_10.dll not found
2021-07-25 11:33:49.570820: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cusolver64_11.dll'; dlerror: cusolver64_11.dll not found
2021-07-25 11:33:49.571813: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cusparse64_11.dll'; dlerror: cusparse64_11.dll not found
Dictionory Size:  232
Load Save model form file ........
2021-07-25 11:33:49.572828: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cudnn64_8.dll'; dlerror: cudnn64_8.dll not found
2021-07-25 11:33:49.573012: W tensorflow/core/common_runtime/gpu/gpu_device.cc:1766] Cannot dlopen some GPU libraries. Please make sure the missing libraries mentioned above are installed properly if you would like to use GPU. Follow the guide at https://www.tensorflow.org/install/gpu for how to download and setup the required libraries for your platform.
Skipping registering GPU devices...
2021-07-25 11:33:49.573631: I tensorflow/core/platform/cpu_feature_guard.cc:142] This TensorFlow binary is optimized with oneAPI Deep Neural Network Library (oneDNN) to use the following CPU instructions in performance-critical operations:  AVX AVX2
To enable them in other operations, rebuild TensorFlow with the appropriate compiler flags.
2021-07-25 11:33:49.574569: I tensorflow/core/common_runtime/gpu/gpu_device.cc:1258] Device interconnect StreamExecutor with strength 1 edge matrix:
2021-07-25 11:33:49.574801: I tensorflow/core/common_runtime/gpu/gpu_device.cc:1264]      
Total no of Sequences (largedataset/test/1_1.txt):23912
2021-07-25 11:33:52.007858: I tensorflow/compiler/mlir/mlir_graph_optimization_pass.cc:176] None of the MLIR Optimization Passes are enabled (registered 2)
Output : 
[[0.9901488  0.00401351 0.0260289 ]]
Total no of Sequences (largedataset/test/2_1.txt):30064
Output : 
[[-4.2950585e-03  9.2160332e-01 -8.0496073e-04]]
Total no of Sequences (largedataset/test/3_1.txt):29882
Output : 
[[0.00305451 0.00474353 0.9754731 ]]

Process finished with exit code 0


Step 8
Run KFold Cross validation
Run python file largesetKfold.py

Output :

"D:\ME Project\covid19\venv\Scripts\python.exe" "D:/ME Project/covid19/largesetKfold.py"
2021-07-23 00:28:20.568287: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cudart64_110.dll'; dlerror: cudart64_110.dll not found
2021-07-23 00:28:20.568497: I tensorflow/stream_executor/cuda/cudart_stub.cc:29] Ignore above cudart dlerror if you do not have a GPU set up on your machine.
Dictionory Size:  24
2021-07-23 00:28:22.460106: I tensorflow/stream_executor/platform/default/dso_loader.cc:53] Successfully opened dynamic library nvcuda.dll
2021-07-23 00:28:23.403686: I tensorflow/core/common_runtime/gpu/gpu_device.cc:1733] Found device 0 with properties: 
pciBusID: 0000:01:00.0 name: GeForce GTX 1650 computeCapability: 7.5
coreClock: 1.56GHz coreCount: 16 deviceMemorySize: 4.00GiB deviceMemoryBandwidth: 119.24GiB/s
2021-07-23 00:28:23.404908: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cudart64_110.dll'; dlerror: cudart64_110.dll not found
2021-07-23 00:28:23.405918: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cublas64_11.dll'; dlerror: cublas64_11.dll not found
2021-07-23 00:28:23.406912: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cublasLt64_11.dll'; dlerror: cublasLt64_11.dll not found
2021-07-23 00:28:23.407892: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cufft64_10.dll'; dlerror: cufft64_10.dll not found
2021-07-23 00:28:23.408865: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'curand64_10.dll'; dlerror: curand64_10.dll not found
2021-07-23 00:28:23.409863: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cusolver64_11.dll'; dlerror: cusolver64_11.dll not found
2021-07-23 00:28:23.410881: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cusparse64_11.dll'; dlerror: cusparse64_11.dll not found
2021-07-23 00:28:23.411873: W tensorflow/stream_executor/platform/default/dso_loader.cc:64] Could not load dynamic library 'cudnn64_8.dll'; dlerror: cudnn64_8.dll not found
2021-07-23 00:28:23.412055: W tensorflow/core/common_runtime/gpu/gpu_device.cc:1766] Cannot dlopen some GPU libraries. Please make sure the missing libraries mentioned above are installed properly if you would like to use GPU. Follow the guide at https://www.tensorflow.org/install/gpu for how to download and setup the required libraries for your platform.
Skipping registering GPU devices...
2021-07-23 00:28:23.412683: I tensorflow/core/platform/cpu_feature_guard.cc:142] This TensorFlow binary is optimized with oneAPI Deep Neural Network Library (oneDNN) to use the following CPU instructions in performance-critical operations:  AVX AVX2
To enable them in other operations, rebuild TensorFlow with the appropriate compiler flags.
2021-07-23 00:28:23.413567: I tensorflow/core/common_runtime/gpu/gpu_device.cc:1258] Device interconnect StreamExecutor with strength 1 edge matrix:
2021-07-23 00:28:23.413737: I tensorflow/core/common_runtime/gpu/gpu_device.cc:1264]      
2021-07-23 00:28:24.432431: I tensorflow/compiler/mlir/mlir_graph_optimization_pass.cc:176] None of the MLIR Optimization Passes are enabled (registered 2)
Epoch 1/10
79/79 [==============================] - 15s 20ms/step - loss: 0.1654 - accuracy: 0.9046
Epoch 2/10
79/79 [==============================] - 2s 19ms/step - loss: 0.0502 - accuracy: 0.9522
Epoch 3/10
79/79 [==============================] - 1s 19ms/step - loss: 0.0478 - accuracy: 0.9492
Epoch 4/10
79/79 [==============================] - 1s 19ms/step - loss: 0.0457 - accuracy: 0.9464
Epoch 5/10
79/79 [==============================] - 2s 20ms/step - loss: 0.0425 - accuracy: 0.9514
Epoch 6/10
79/79 [==============================] - 1s 19ms/step - loss: 0.0433 - accuracy: 0.9479
Epoch 7/10
79/79 [==============================] - 2s 19ms/step - loss: 0.0423 - accuracy: 0.9487
Epoch 8/10
79/79 [==============================] - 1s 19ms/step - loss: 0.0400 - accuracy: 0.9499
Epoch 9/10
79/79 [==============================] - 2s 19ms/step - loss: 0.0409 - accuracy: 0.9494
Epoch 10/10
79/79 [==============================] - 1s 19ms/step - loss: 0.0419 - accuracy: 0.9459
[0.03016556426882744, 0.9532185196876526]
loss: 3.02%
accuracy: 95.32%
File : largedataset\kmer\Beata-SARS 2_0-10000.csv\kemr-2-records.pickle K : 2
[0.03154386207461357, 0.9509319067001343]
loss: 3.15%
accuracy: 95.09%
time in MS : 1294.3792343139648
File : largedataset\kmer\Beata-SARS 2_10000-20000.csv\kemr-2-records.pickle K : 2
[0.03155294060707092, 0.9509319067001343]
loss: 3.16%
accuracy: 95.09%
time in MS : 1362.6015186309814
File : largedataset\kmer\Beata-SARS 2_20000-30000.csv\kemr-2-records.pickle K : 2
[0.03156068176031113, 0.9509319067001343]
loss: 3.16%
accuracy: 95.09%
time in MS : 1338.5217189788818
File : largedataset\kmer\Beata-SARS 2_30000-40000.csv\kemr-2-records.pickle K : 2
[0.031525690108537674, 0.9509319067001343]
loss: 3.15%
accuracy: 95.09%
time in MS : 1423.771858215332
File : largedataset\kmer\Beata-SARS 2_40000-50000.csv\kemr-2-records.pickle K : 2
[0.031522590667009354, 0.9509319067001343]
loss: 3.15%
accuracy: 95.09%
time in MS : 1331.1750888824463
File : largedataset\kmer\Beata-SARS 2_50000-60000.csv\kemr-2-records.pickle K : 2
[0.0315338559448719, 0.9509319067001343]
loss: 3.15%
accuracy: 95.09%
time in MS : 1620.429515838623
File : largedataset\kmer\Beata-SARS 2_60000-70000.csv\kemr-2-records.pickle K : 2
[0.03153328597545624, 0.9509319067001343]
loss: 3.15%
accuracy: 95.09%
time in MS : 1327.8250694274902
File : largedataset\kmer\Beata-SARS 2_70000-80000.csv\kemr-2-records.pickle K : 2
[0.031537335366010666, 0.9509319067001343]
loss: 3.15%
accuracy: 95.09%
time in MS : 1330.521583557129
File : largedataset\kmer\Beata-SARS 2_80000-90000.csv\kemr-2-records.pickle K : 2
[0.03153064846992493, 0.9509319067001343]
loss: 3.15%
accuracy: 95.09%
time in MS : 1329.8304080963135
File : largedataset\kmer\Beata-SARS 2_90000-100000.csv\kemr-2-records.pickle K : 2
[0.03153049573302269, 0.9509319067001343]
loss: 3.15%
accuracy: 95.09%
time in MS : 1356.1856746673584
Dictionory Size:  83
Epoch 1/10
79/79 [==============================] - 9s 57ms/step - loss: 0.1776 - accuracy: 0.8090
Epoch 2/10
79/79 [==============================] - 5s 58ms/step - loss: 0.0527 - accuracy: 0.9495
Epoch 3/10
79/79 [==============================] - 4s 57ms/step - loss: 0.0510 - accuracy: 0.9454
Epoch 4/10
79/79 [==============================] - 5s 60ms/step - loss: 0.0472 - accuracy: 0.9485
Epoch 5/10
79/79 [==============================] - 5s 57ms/step - loss: 0.0447 - accuracy: 0.9462
Epoch 6/10
79/79 [==============================] - 5s 58ms/step - loss: 0.0445 - accuracy: 0.9434
Epoch 7/10
79/79 [==============================] - 5s 60ms/step - loss: 0.0418 - accuracy: 0.9487
Epoch 8/10
79/79 [==============================] - 5s 58ms/step - loss: 0.0446 - accuracy: 0.9432
Epoch 9/10
79/79 [==============================] - 5s 58ms/step - loss: 0.0378 - accuracy: 0.9512
Epoch 10/10
79/79 [==============================] - 5s 58ms/step - loss: 0.0381 - accuracy: 0.9504
[0.030500667169690132, 0.9532185196876526]
loss: 3.05%
accuracy: 95.32%
File : largedataset\kmer\Beata-SARS 2_0-10000.csv\kemr-3-records.pickle K : 3
[0.03176921233534813, 0.9509319067001343]
loss: 3.18%
accuracy: 95.09%
time in MS : 3963.700771331787
File : largedataset\kmer\Beata-SARS 2_10000-20000.csv\kemr-3-records.pickle K : 3
[0.03202201798558235, 0.9509319067001343]
loss: 3.20%
accuracy: 95.09%
time in MS : 4008.4431171417236
File : largedataset\kmer\Beata-SARS 2_20000-30000.csv\kemr-3-records.pickle K : 3
[0.03135252371430397, 0.9509319067001343]
loss: 3.14%
accuracy: 95.09%
time in MS : 4038.771629333496
File : largedataset\kmer\Beata-SARS 2_30000-40000.csv\kemr-3-records.pickle K : 3
[0.03113257884979248, 0.9509319067001343]
loss: 3.11%
accuracy: 95.09%
time in MS : 3998.6767768859863
File : largedataset\kmer\Beata-SARS 2_40000-50000.csv\kemr-3-records.pickle K : 3
[0.030823439359664917, 0.9509319067001343]
loss: 3.08%
accuracy: 95.09%
time in MS : 3986.5875244140625
File : largedataset\kmer\Beata-SARS 2_50000-60000.csv\kemr-3-records.pickle K : 3
[0.032096751034259796, 0.9509319067001343]
loss: 3.21%
accuracy: 95.09%
time in MS : 3964.921236038208
File : largedataset\kmer\Beata-SARS 2_60000-70000.csv\kemr-3-records.pickle K : 3
[0.032138142734766006, 0.9509319067001343]
loss: 3.21%
accuracy: 95.09%
time in MS : 4002.9027462005615
File : largedataset\kmer\Beata-SARS 2_70000-80000.csv\kemr-3-records.pickle K : 3
[0.032148487865924835, 0.9509319067001343]
loss: 3.21%
accuracy: 95.09%
time in MS : 4064.344644546509
File : largedataset\kmer\Beata-SARS 2_80000-90000.csv\kemr-3-records.pickle K : 3
[0.032100822776556015, 0.9509319067001343]
loss: 3.21%
accuracy: 95.09%
time in MS : 3976.9961833953857
File : largedataset\kmer\Beata-SARS 2_90000-100000.csv\kemr-3-records.pickle K : 3
[0.03209519013762474, 0.9509319067001343]
loss: 3.21%
accuracy: 95.09%
time in MS : 4464.929580688477
Dictionory Size:  177
Epoch 1/10
79/79 [==============================] - 15s 124ms/step - loss: 0.1843 - accuracy: 0.9390
Epoch 2/10
79/79 [==============================] - 10s 124ms/step - loss: 0.0563 - accuracy: 0.9462
Epoch 3/10
79/79 [==============================] - 10s 124ms/step - loss: 0.0482 - accuracy: 0.9499
Epoch 4/10
79/79 [==============================] - 10s 124ms/step - loss: 0.0498 - accuracy: 0.9449
Epoch 5/10
79/79 [==============================] - 10s 123ms/step - loss: 0.0408 - accuracy: 0.9538
Epoch 6/10
79/79 [==============================] - 10s 124ms/step - loss: 0.0451 - accuracy: 0.9445
Epoch 7/10
79/79 [==============================] - 10s 124ms/step - loss: 0.0403 - accuracy: 0.9502
Epoch 8/10
79/79 [==============================] - 10s 124ms/step - loss: 0.0409 - accuracy: 0.9475
Epoch 9/10
79/79 [==============================] - 10s 124ms/step - loss: 0.0399 - accuracy: 0.9475
Epoch 10/10
79/79 [==============================] - 10s 125ms/step - loss: 0.0355 - accuracy: 0.9525
[0.02724866382777691, 0.9532185196876526]
loss: 2.72%
accuracy: 95.32%
File : largedataset\kmer\Beata-SARS 2_0-10000.csv\kemr-4-records.pickle K : 4
[0.0284706000238657, 0.9509319067001343]
loss: 2.85%
accuracy: 95.09%
time in MS : 9132.758617401123
File : largedataset\kmer\Beata-SARS 2_10000-20000.csv\kemr-4-records.pickle K : 4
[0.028669895604252815, 0.9509319067001343]
loss: 2.87%
accuracy: 95.09%
time in MS : 9327.707052230835
File : largedataset\kmer\Beata-SARS 2_20000-30000.csv\kemr-4-records.pickle K : 4
[0.02841312251985073, 0.9509319067001343]
loss: 2.84%
accuracy: 95.09%
time in MS : 9322.171449661255
File : largedataset\kmer\Beata-SARS 2_30000-40000.csv\kemr-4-records.pickle K : 4
[0.028276273980736732, 0.9509319067001343]
loss: 2.83%
accuracy: 95.09%
time in MS : 9115.957021713257
File : largedataset\kmer\Beata-SARS 2_40000-50000.csv\kemr-4-records.pickle K : 4
[0.02808069810271263, 0.9509319067001343]
loss: 2.81%
accuracy: 95.09%
time in MS : 9348.109245300293
File : largedataset\kmer\Beata-SARS 2_50000-60000.csv\kemr-4-records.pickle K : 4
[0.02876536175608635, 0.9509319067001343]
loss: 2.88%
accuracy: 95.09%
time in MS : 9408.817052841187
File : largedataset\kmer\Beata-SARS 2_60000-70000.csv\kemr-4-records.pickle K : 4
[0.02889033779501915, 0.9509319067001343]
loss: 2.89%
accuracy: 95.09%
time in MS : 9196.337223052979
File : largedataset\kmer\Beata-SARS 2_70000-80000.csv\kemr-4-records.pickle K : 4
[0.028851795941591263, 0.9509319067001343]
loss: 2.89%
accuracy: 95.09%
time in MS : 9150.588512420654
File : largedataset\kmer\Beata-SARS 2_80000-90000.csv\kemr-4-records.pickle K : 4
[0.028786085546016693, 0.9509319067001343]
loss: 2.88%
accuracy: 95.09%
time in MS : 9168.059349060059
File : largedataset\kmer\Beata-SARS 2_90000-100000.csv\kemr-4-records.pickle K : 4
[0.02877316251397133, 0.9509319067001343]
loss: 2.88%
accuracy: 95.09%
time in MS : 9252.127885818481
Dictionory Size:  203
Epoch 1/10
79/79 [==============================] - 16s 145ms/step - loss: 0.1860 - accuracy: 0.7771
Epoch 2/10
79/79 [==============================] - 12s 148ms/step - loss: 0.0494 - accuracy: 0.9502
Epoch 3/10
79/79 [==============================] - 11s 145ms/step - loss: 0.0480 - accuracy: 0.9489
Epoch 4/10
79/79 [==============================] - 12s 148ms/step - loss: 0.0435 - accuracy: 0.9505
Epoch 5/10
79/79 [==============================] - 11s 144ms/step - loss: 0.0426 - accuracy: 0.9503
Epoch 6/10
79/79 [==============================] - 11s 145ms/step - loss: 0.0449 - accuracy: 0.9451
Epoch 7/10
79/79 [==============================] - 11s 144ms/step - loss: 0.0407 - accuracy: 0.9491
Epoch 8/10
79/79 [==============================] - 11s 145ms/step - loss: 0.0397 - accuracy: 0.9501
Epoch 9/10
79/79 [==============================] - 12s 148ms/step - loss: 0.0405 - accuracy: 0.9430
Epoch 10/10
79/79 [==============================] - 11s 145ms/step - loss: 0.0430 - accuracy: 0.9439
[0.02969461679458618, 0.9532185196876526]
loss: 2.97%
accuracy: 95.32%
File : largedataset\kmer\Beata-SARS 2_0-10000.csv\kemr-5-records.pickle K : 5
[0.031018709763884544, 0.9509319067001343]
loss: 3.10%
accuracy: 95.09%
time in MS : 10738.673686981201
File : largedataset\kmer\Beata-SARS 2_10000-20000.csv\kemr-5-records.pickle K : 5
[0.031110893934965134, 0.9509319067001343]
loss: 3.11%
accuracy: 95.09%
time in MS : 11030.6396484375
File : largedataset\kmer\Beata-SARS 2_20000-30000.csv\kemr-5-records.pickle K : 5
[0.0309904757887125, 0.9509319067001343]
loss: 3.10%
accuracy: 95.09%
time in MS : 10933.05516242981
File : largedataset\kmer\Beata-SARS 2_30000-40000.csv\kemr-5-records.pickle K : 5
[0.03091108240187168, 0.9509319067001343]
loss: 3.09%
accuracy: 95.09%
time in MS : 10815.652132034302
File : largedataset\kmer\Beata-SARS 2_40000-50000.csv\kemr-5-records.pickle K : 5
[0.03083687461912632, 0.9509319067001343]
loss: 3.08%
accuracy: 95.09%
time in MS : 11649.707555770874
File : largedataset\kmer\Beata-SARS 2_50000-60000.csv\kemr-5-records.pickle K : 5
[0.03111691027879715, 0.9509319067001343]
loss: 3.11%
accuracy: 95.09%
time in MS : 11191.571712493896
File : largedataset\kmer\Beata-SARS 2_60000-70000.csv\kemr-5-records.pickle K : 5
[0.03110889531672001, 0.9509319067001343]
loss: 3.11%
accuracy: 95.09%
time in MS : 11033.66994857788
File : largedataset\kmer\Beata-SARS 2_70000-80000.csv\kemr-5-records.pickle K : 5
[0.031128402799367905, 0.9509319067001343]
loss: 3.11%
accuracy: 95.09%
time in MS : 10682.048797607422
File : largedataset\kmer\Beata-SARS 2_80000-90000.csv\kemr-5-records.pickle K : 5
[0.031084775924682617, 0.9509319067001343]
loss: 3.11%
accuracy: 95.09%
time in MS : 11241.275548934937
File : largedataset\kmer\Beata-SARS 2_90000-100000.csv\kemr-5-records.pickle K : 5
[0.031109696254134178, 0.9509319067001343]
loss: 3.11%
accuracy: 95.09%
time in MS : 11279.924154281616
Dictionory Size:  220
Epoch 1/10
79/79 [==============================] - 17s 155ms/step - loss: 0.2217 - accuracy: 0.8708
Epoch 2/10
79/79 [==============================] - 12s 155ms/step - loss: 0.0552 - accuracy: 0.9518
Epoch 3/10
79/79 [==============================] - 12s 154ms/step - loss: 0.0503 - accuracy: 0.9473
Epoch 4/10
79/79 [==============================] - 12s 155ms/step - loss: 0.0402 - accuracy: 0.9611
Epoch 5/10
79/79 [==============================] - 12s 155ms/step - loss: 0.0319 - accuracy: 0.9747
Epoch 6/10
79/79 [==============================] - 12s 155ms/step - loss: 0.0288 - accuracy: 0.9744
Epoch 7/10
79/79 [==============================] - 12s 155ms/step - loss: 0.0281 - accuracy: 0.9740
Epoch 8/10
79/79 [==============================] - 12s 155ms/step - loss: 0.0252 - accuracy: 0.9724
Epoch 9/10
79/79 [==============================] - 12s 155ms/step - loss: 0.0227 - accuracy: 0.9750
Epoch 10/10
79/79 [==============================] - 12s 155ms/step - loss: 0.0178 - accuracy: 0.9858
[0.003731846110895276, 0.9990933537483215]
loss: 0.37%
accuracy: 99.91%
File : largedataset\kmer\Beata-SARS 2_0-10000.csv\kemr-6-records.pickle K : 6
[0.0037988852709531784, 0.9992392659187317]
loss: 0.38%
accuracy: 99.92%
time in MS : 11716.45975112915
File : largedataset\kmer\Beata-SARS 2_10000-20000.csv\kemr-6-records.pickle K : 6
[0.004230257123708725, 0.9986686706542969]
loss: 0.42%
accuracy: 99.87%
time in MS : 11646.255016326904
File : largedataset\kmer\Beata-SARS 2_20000-30000.csv\kemr-6-records.pickle K : 6
[0.004937455058097839, 0.9990490674972534]
loss: 0.49%
accuracy: 99.90%
time in MS : 12103.19972038269
File : largedataset\kmer\Beata-SARS 2_30000-40000.csv\kemr-6-records.pickle K : 6
[0.0038782835472375154, 0.9998098015785217]
loss: 0.39%
accuracy: 99.98%
time in MS : 11776.179790496826
File : largedataset\kmer\Beata-SARS 2_40000-50000.csv\kemr-6-records.pickle K : 6
[0.004819868598133326, 0.99942946434021]
loss: 0.48%
accuracy: 99.94%
time in MS : 12017.6260471344
File : largedataset\kmer\Beata-SARS 2_50000-60000.csv\kemr-6-records.pickle K : 6
[0.004105071071535349, 0.9998098015785217]
loss: 0.41%
accuracy: 99.98%
time in MS : 11805.926322937012
File : largedataset\kmer\Beata-SARS 2_60000-70000.csv\kemr-6-records.pickle K : 6
[0.004618806764483452, 1.0]
loss: 0.46%
accuracy: 100.00%
time in MS : 11974.982261657715
File : largedataset\kmer\Beata-SARS 2_70000-80000.csv\kemr-6-records.pickle K : 6
[0.0033897205721586943, 0.9999049305915833]
loss: 0.34%
accuracy: 99.99%
time in MS : 12390.347480773926
File : largedataset\kmer\Beata-SARS 2_80000-90000.csv\kemr-6-records.pickle K : 6
[0.0038844014052301645, 0.9999049305915833]
loss: 0.39%
accuracy: 99.99%
time in MS : 11896.863222122192
File : largedataset\kmer\Beata-SARS 2_90000-100000.csv\kemr-6-records.pickle K : 6
[0.004029158502817154, 0.9999049305915833]
loss: 0.40%
accuracy: 99.99%
time in MS : 12226.5784740448
Dictionory Size:  226
Epoch 1/10
79/79 [==============================] - 17s 159ms/step - loss: 0.2074 - accuracy: 0.9326
Epoch 2/10
79/79 [==============================] - 13s 161ms/step - loss: 0.0615 - accuracy: 0.9445
Epoch 3/10
79/79 [==============================] - 13s 162ms/step - loss: 0.0512 - accuracy: 0.9533
Epoch 4/10
79/79 [==============================] - 13s 164ms/step - loss: 0.0463 - accuracy: 0.9504
Epoch 5/10
79/79 [==============================] - 13s 162ms/step - loss: 0.0366 - accuracy: 0.9740
Epoch 6/10
79/79 [==============================] - 13s 163ms/step - loss: 0.0314 - accuracy: 0.9751
Epoch 7/10
79/79 [==============================] - 13s 161ms/step - loss: 0.0289 - accuracy: 0.9737
Epoch 8/10
79/79 [==============================] - 13s 160ms/step - loss: 0.0269 - accuracy: 0.9741
Epoch 9/10
79/79 [==============================] - 13s 161ms/step - loss: 0.0253 - accuracy: 0.9747
Epoch 10/10
79/79 [==============================] - 13s 161ms/step - loss: 0.0257 - accuracy: 0.9727
[0.012986252084374428, 0.9767905473709106]
loss: 1.30%
accuracy: 97.68%
File : largedataset\kmer\Beata-SARS 2_0-10000.csv\kemr-7-records.pickle K : 7
[0.013473709113895893, 0.9758463501930237]
loss: 1.35%
accuracy: 97.58%
time in MS : 12124.405145645142
File : largedataset\kmer\Beata-SARS 2_10000-20000.csv\kemr-7-records.pickle K : 7
[0.015945594757795334, 0.9758463501930237]
loss: 1.59%
accuracy: 97.58%
time in MS : 11906.766176223755
File : largedataset\kmer\Beata-SARS 2_20000-30000.csv\kemr-7-records.pickle K : 7
[0.013669201172888279, 0.9758463501930237]
loss: 1.37%
accuracy: 97.58%
time in MS : 12158.296823501587
File : largedataset\kmer\Beata-SARS 2_30000-40000.csv\kemr-7-records.pickle K : 7
[0.0134554049000144, 0.9758463501930237]
loss: 1.35%
accuracy: 97.58%
time in MS : 12010.496377944946
File : largedataset\kmer\Beata-SARS 2_40000-50000.csv\kemr-7-records.pickle K : 7
[0.013349867425858974, 0.9755610227584839]
loss: 1.33%
accuracy: 97.56%
time in MS : 12099.116325378418
File : largedataset\kmer\Beata-SARS 2_50000-60000.csv\kemr-7-records.pickle K : 7
[0.013030564412474632, 0.9758463501930237]
loss: 1.30%
accuracy: 97.58%
time in MS : 11929.979085922241
File : largedataset\kmer\Beata-SARS 2_60000-70000.csv\kemr-7-records.pickle K : 7
[0.016801994293928146, 0.9757512211799622]
loss: 1.68%
accuracy: 97.58%
time in MS : 12200.264930725098
File : largedataset\kmer\Beata-SARS 2_70000-80000.csv\kemr-7-records.pickle K : 7
[0.015513945370912552, 0.9758463501930237]
loss: 1.55%
accuracy: 97.58%
time in MS : 12041.982173919678
File : largedataset\kmer\Beata-SARS 2_80000-90000.csv\kemr-7-records.pickle K : 7
[0.01600525714457035, 0.9758463501930237]
loss: 1.60%
accuracy: 97.58%
time in MS : 12167.611598968506
File : largedataset\kmer\Beata-SARS 2_90000-100000.csv\kemr-7-records.pickle K : 7
[0.01707998663187027, 0.9757512211799622]
loss: 1.71%
accuracy: 97.58%
time in MS : 12720.423936843872
Dictionory Size:  232
Epoch 1/10
79/79 [==============================] - 18s 164ms/step - loss: 0.2013 - accuracy: 0.8692
Epoch 2/10
79/79 [==============================] - 13s 166ms/step - loss: 0.0403 - accuracy: 0.9502
Epoch 3/10
79/79 [==============================] - 13s 166ms/step - loss: 0.0313 - accuracy: 0.9716
Epoch 4/10
79/79 [==============================] - 13s 167ms/step - loss: 0.0275 - accuracy: 0.9737
Epoch 5/10
79/79 [==============================] - 13s 165ms/step - loss: 0.0260 - accuracy: 0.9701
Epoch 6/10
79/79 [==============================] - 13s 164ms/step - loss: 0.0228 - accuracy: 0.9786
Epoch 7/10
79/79 [==============================] - 13s 165ms/step - loss: 0.0216 - accuracy: 0.9756
Epoch 8/10
79/79 [==============================] - 13s 165ms/step - loss: 0.0191 - accuracy: 0.9790
Epoch 9/10
79/79 [==============================] - 13s 164ms/step - loss: 0.0151 - accuracy: 0.9953
Epoch 10/10
79/79 [==============================] - 13s 164ms/step - loss: 0.0126 - accuracy: 0.9980
[0.0008430792368017137, 0.9998186826705933]
loss: 0.08%
accuracy: 99.98%
File : largedataset\kmer\Beata-SARS 2_0-10000.csv\kemr-8-records.pickle K : 8
[0.0008506635203957558, 0.9999049305915833]
loss: 0.09%
accuracy: 99.99%
time in MS : 12321.938514709473
File : largedataset\kmer\Beata-SARS 2_10000-20000.csv\kemr-8-records.pickle K : 8
[0.0008765649981796741, 1.0]
loss: 0.09%
accuracy: 100.00%
time in MS : 12018.68748664856
File : largedataset\kmer\Beata-SARS 2_20000-30000.csv\kemr-8-records.pickle K : 8
[0.0007671874482184649, 1.0]
loss: 0.08%
accuracy: 100.00%
time in MS : 12392.229557037354
File : largedataset\kmer\Beata-SARS 2_30000-40000.csv\kemr-8-records.pickle K : 8
[0.0008528263424523175, 0.999714732170105]
loss: 0.09%
accuracy: 99.97%
time in MS : 12189.375162124634
File : largedataset\kmer\Beata-SARS 2_40000-50000.csv\kemr-8-records.pickle K : 8
[0.0008602025336585939, 0.999714732170105]
loss: 0.09%
accuracy: 99.97%
time in MS : 12231.632947921753
File : largedataset\kmer\Beata-SARS 2_50000-60000.csv\kemr-8-records.pickle K : 8
[0.0008175470284186304, 0.9998098015785217]
loss: 0.08%
accuracy: 99.98%
time in MS : 12417.891502380371
File : largedataset\kmer\Beata-SARS 2_60000-70000.csv\kemr-8-records.pickle K : 8
[0.0008793738088570535, 0.9996196031570435]
loss: 0.09%
accuracy: 99.96%
time in MS : 12571.396112442017
File : largedataset\kmer\Beata-SARS 2_70000-80000.csv\kemr-8-records.pickle K : 8
[0.0008122568833641708, 0.9999049305915833]
loss: 0.08%
accuracy: 99.99%
time in MS : 12286.807775497437
File : largedataset\kmer\Beata-SARS 2_80000-90000.csv\kemr-8-records.pickle K : 8
[0.0007995497435331345, 1.0]
loss: 0.08%
accuracy: 100.00%
time in MS : 12479.99358177185
File : largedataset\kmer\Beata-SARS 2_90000-100000.csv\kemr-8-records.pickle K : 8
[0.0008409721776843071, 0.9999049305915833]
loss: 0.08%
accuracy: 99.99%
time in MS : 12346.084356307983
Dictionory Size:  237
Epoch 1/10
79/79 [==============================] - 18s 168ms/step - loss: 0.2086 - accuracy: 0.9075
Epoch 2/10
79/79 [==============================] - 13s 169ms/step - loss: 0.0640 - accuracy: 0.9492
Epoch 3/10
79/79 [==============================] - 13s 170ms/step - loss: 0.0459 - accuracy: 0.9488
Epoch 4/10
79/79 [==============================] - 13s 171ms/step - loss: 0.0312 - accuracy: 0.9654
Epoch 5/10
79/79 [==============================] - 14s 171ms/step - loss: 0.0235 - accuracy: 0.9749
Epoch 6/10
79/79 [==============================] - 14s 171ms/step - loss: 0.0220 - accuracy: 0.9804
Epoch 7/10
79/79 [==============================] - 13s 171ms/step - loss: 0.0196 - accuracy: 0.9824
Epoch 8/10
79/79 [==============================] - 14s 172ms/step - loss: 0.0168 - accuracy: 0.9917
Epoch 9/10
79/79 [==============================] - 14s 172ms/step - loss: 0.0140 - accuracy: 0.9936
Epoch 10/10
79/79 [==============================] - 14s 171ms/step - loss: 0.0120 - accuracy: 0.9951
[0.0005599408177658916, 0.9996373653411865]
loss: 0.06%
accuracy: 99.96%
File : largedataset\kmer\Beata-SARS 2_0-10000.csv\kemr-9-records.pickle K : 9
[0.000546793220564723, 0.9998098015785217]
loss: 0.05%
accuracy: 99.98%
time in MS : 12457.13496208191
File : largedataset\kmer\Beata-SARS 2_10000-20000.csv\kemr-9-records.pickle K : 9
[0.0005885927239432931, 0.999714732170105]
loss: 0.06%
accuracy: 99.97%
time in MS : 12682.460069656372
File : largedataset\kmer\Beata-SARS 2_20000-30000.csv\kemr-9-records.pickle K : 9
[0.0006874827668070793, 0.9998098015785217]
loss: 0.07%
accuracy: 99.98%
time in MS : 12600.626468658447
File : largedataset\kmer\Beata-SARS 2_30000-40000.csv\kemr-9-records.pickle K : 9
[0.0006669262074865401, 0.9998098015785217]
loss: 0.07%
accuracy: 99.98%
time in MS : 12283.77890586853
File : largedataset\kmer\Beata-SARS 2_40000-50000.csv\kemr-9-records.pickle K : 9
[0.0007083664531819522, 0.999714732170105]
loss: 0.07%
accuracy: 99.97%
time in MS : 12459.28955078125
File : largedataset\kmer\Beata-SARS 2_50000-60000.csv\kemr-9-records.pickle K : 9
[0.000569824711419642, 0.999714732170105]
loss: 0.06%
accuracy: 99.97%
time in MS : 12777.565240859985
File : largedataset\kmer\Beata-SARS 2_60000-70000.csv\kemr-9-records.pickle K : 9
[0.0005410824087448418, 0.9998098015785217]
loss: 0.05%
accuracy: 99.98%
time in MS : 12469.191074371338
File : largedataset\kmer\Beata-SARS 2_70000-80000.csv\kemr-9-records.pickle K : 9
[0.0005406642449088395, 0.9998098015785217]
loss: 0.05%
accuracy: 99.98%
time in MS : 12414.276838302612
File : largedataset\kmer\Beata-SARS 2_80000-90000.csv\kemr-9-records.pickle K : 9
[0.0005380380898714066, 0.9998098015785217]
loss: 0.05%
accuracy: 99.98%
time in MS : 12273.838520050049
File : largedataset\kmer\Beata-SARS 2_90000-100000.csv\kemr-9-records.pickle K : 9
[0.0005372482119128108, 0.9998098015785217]
loss: 0.05%
accuracy: 99.98%
time in MS : 13120.403051376343
Dictionory Size:  242
Epoch 1/10
79/79 [==============================] - 19s 180ms/step - loss: 0.2052 - accuracy: 0.8508
Epoch 2/10
79/79 [==============================] - 13s 170ms/step - loss: 0.0552 - accuracy: 0.9503
Epoch 3/10
79/79 [==============================] - 13s 170ms/step - loss: 0.0437 - accuracy: 0.9460
Epoch 4/10
79/79 [==============================] - 13s 168ms/step - loss: 0.0290 - accuracy: 0.9708
Epoch 5/10
79/79 [==============================] - 13s 168ms/step - loss: 0.0286 - accuracy: 0.9676
Epoch 6/10
79/79 [==============================] - 13s 169ms/step - loss: 0.0252 - accuracy: 0.9744
Epoch 7/10
79/79 [==============================] - 13s 169ms/step - loss: 0.0230 - accuracy: 0.9734
Epoch 8/10
79/79 [==============================] - 13s 170ms/step - loss: 0.0215 - accuracy: 0.9735
Epoch 9/10
79/79 [==============================] - 13s 169ms/step - loss: 0.0211 - accuracy: 0.9724
Epoch 10/10
79/79 [==============================] - 13s 169ms/step - loss: 0.0189 - accuracy: 0.9761
[0.008180545642971992, 0.9769719243049622]
loss: 0.82%
accuracy: 97.70%
File : largedataset\kmer\Beata-SARS 2_0-10000.csv\kemr-10-records.pickle K : 10
[0.008561383932828903, 0.9759414196014404]
loss: 0.86%
accuracy: 97.59%
time in MS : 12863.158464431763
File : largedataset\kmer\Beata-SARS 2_10000-20000.csv\kemr-10-records.pickle K : 10
[0.008585076779127121, 0.9759414196014404]
loss: 0.86%
accuracy: 97.59%
time in MS : 13521.075010299683
File : largedataset\kmer\Beata-SARS 2_20000-30000.csv\kemr-10-records.pickle K : 10
[0.008587994612753391, 0.9759414196014404]
loss: 0.86%
accuracy: 97.59%
time in MS : 13051.905393600464
File : largedataset\kmer\Beata-SARS 2_30000-40000.csv\kemr-10-records.pickle K : 10
[0.008572427555918694, 0.9759414196014404]
loss: 0.86%
accuracy: 97.59%
time in MS : 13204.582452774048
File : largedataset\kmer\Beata-SARS 2_40000-50000.csv\kemr-10-records.pickle K : 10
[0.008544114418327808, 0.9759414196014404]
loss: 0.85%
accuracy: 97.59%
time in MS : 12918.13611984253
File : largedataset\kmer\Beata-SARS 2_50000-60000.csv\kemr-10-records.pickle K : 10
[0.008543661795556545, 0.9759414196014404]
loss: 0.85%
accuracy: 97.59%
time in MS : 13249.646663665771
File : largedataset\kmer\Beata-SARS 2_60000-70000.csv\kemr-10-records.pickle K : 10
[0.00850990042090416, 0.9759414196014404]
loss: 0.85%
accuracy: 97.59%
time in MS : 13043.690204620361
File : largedataset\kmer\Beata-SARS 2_70000-80000.csv\kemr-10-records.pickle K : 10
[0.008512143976986408, 0.9759414196014404]
loss: 0.85%
accuracy: 97.59%
time in MS : 12852.689266204834
File : largedataset\kmer\Beata-SARS 2_80000-90000.csv\kemr-10-records.pickle K : 10
[0.008510162122547626, 0.9759414196014404]
loss: 0.85%
accuracy: 97.59%
time in MS : 12984.0989112854
File : largedataset\kmer\Beata-SARS 2_90000-100000.csv\kemr-10-records.pickle K : 10
[0.008511451072990894, 0.9759414196014404]
loss: 0.85%
accuracy: 97.59%
time in MS : 13088.525533676147

Process finished with exit code 0
