I tensorflow/core/common_runtime/gpu/gpu_device.cc:839] Creating TensorFlow device (/gpu:0) -> (device: 0, name: GeForce GTX 980, pci bus id: 0000:07:00.0)
Exception AssertionError: AssertionError("Nesting violated for default stack of <type 'weakref'> objects",) in <bound method InteractiveSession.__del__ of <tensorflow.python.client.session.InteractiveSession object at 0x7f96edd01590>> ignored
  tensorlayer:Instantiate InputLayer input_layer (?, 784)
  tensorlayer:Instantiate DropoutLayer drop1: keep: 0.800000
  tensorlayer:Instantiate DenseLayer relu1: 800, <function relu at 0x7f97386e2578>
  tensorlayer:Instantiate DropoutLayer drop2: keep: 0.500000
  tensorlayer:Instantiate DenseLayer relu2: 800, <function relu at 0x7f97386e2578>
  tensorlayer:Instantiate DropoutLayer drop3: keep: 0.500000
  tensorlayer:Instantiate DenseLayer output_layer: 10, <function identity at 0x7f97100e0758>
  param 0: (784, 800) (mean: -0.000044, median: -0.000083, std: 0.087911)   relu1/W:0
  param 1: (800,) (mean: 0.000000, median: 0.000000, std: 0.000000)   relu1/b:0
  param 2: (800, 800) (mean: 0.000086, median: 0.000174, std: 0.087993)   relu2/W:0
  param 3: (800,) (mean: 0.000000, median: 0.000000, std: 0.000000)   relu2/b:0
  param 4: (800, 10) (mean: -0.000220, median: -0.000951, std: 0.087175)   output_layer/W:0
  param 5: (10,) (mean: 0.000000, median: 0.000000, std: 0.000000)   output_layer/b:0
  num of params: 1276810
  layer 0: Tensor("dropout/mul_1:0", shape=(?, 784), dtype=float32)
  layer 1: Tensor("Relu:0", shape=(?, 800), dtype=float32)
  layer 2: Tensor("dropout_1/mul_1:0", shape=(?, 800), dtype=float32)
  layer 3: Tensor("Relu_1:0", shape=(?, 800), dtype=float32)
  layer 4: Tensor("dropout_2/mul_1:0", shape=(?, 800), dtype=float32)
  layer 5: Tensor("add_2:0", shape=(?, 10), dtype=float32)
Start training the network ...
Epoch 1 of 200 took 0.731579s
   val loss: 0.562035
   val acc: 0.825000
Epoch 5 of 200 took 0.557835s
   val loss: 0.286251
   val acc: 0.916000
Epoch 10 of 200 took 0.558575s
   val loss: 0.222106
   val acc: 0.937500
Epoch 15 of 200 took 0.575262s
   val loss: 0.188165
   val acc: 0.948100
Epoch 20 of 200 took 0.564921s
   val loss: 0.164434
   val acc: 0.955400
Epoch 25 of 200 took 0.572334s
   val loss: 0.145848
   val acc: 0.960100
Epoch 30 of 200 took 0.579468s
   val loss: 0.132819
   val acc: 0.963700
Epoch 35 of 200 took 0.561392s
   val loss: 0.122657
   val acc: 0.966300
Epoch 40 of 200 took 0.564490s
   val loss: 0.113542
   val acc: 0.968400
Epoch 45 of 200 took 0.569971s
   val loss: 0.106994
   val acc: 0.969100
Epoch 50 of 200 took 0.573973s
   val loss: 0.099668
   val acc: 0.971400
Epoch 55 of 200 took 0.555727s
   val loss: 0.094177
   val acc: 0.972400
Epoch 60 of 200 took 0.575835s
   val loss: 0.091001
   val acc: 0.973500
Epoch 65 of 200 took 0.584385s
   val loss: 0.087226
   val acc: 0.973800
Epoch 70 of 200 took 0.568456s
   val loss: 0.083294
   val acc: 0.975000
Epoch 75 of 200 took 0.563503s
   val loss: 0.079863
   val acc: 0.976700
Epoch 80 of 200 took 0.570911s
   val loss: 0.077562
   val acc: 0.977200
Epoch 85 of 200 took 0.568649s
   val loss: 0.075622
   val acc: 0.978000
Epoch 90 of 200 took 0.572381s
   val loss: 0.073526
   val acc: 0.977800
Epoch 95 of 200 took 0.573557s
   val loss: 0.071414
   val acc: 0.979100
Epoch 100 of 200 took 0.573976s
   val loss: 0.069486
   val acc: 0.980200
Epoch 105 of 200 took 0.566601s
   val loss: 0.068012
   val acc: 0.980900
Epoch 110 of 200 took 0.559803s
   val loss: 0.066410
   val acc: 0.980700
Epoch 115 of 200 took 0.572070s
   val loss: 0.065095
   val acc: 0.980900
Epoch 120 of 200 took 0.565401s
   val loss: 0.063958
   val acc: 0.981500
Epoch 125 of 200 took 0.572880s
   val loss: 0.063724
   val acc: 0.982100
Epoch 130 of 200 took 0.560457s
   val loss: 0.062261
   val acc: 0.982800
Epoch 135 of 200 took 0.565308s
   val loss: 0.061522
   val acc: 0.982500
Epoch 140 of 200 took 0.566607s
   val loss: 0.060634
   val acc: 0.983000
Epoch 145 of 200 took 0.557342s
   val loss: 0.059505
   val acc: 0.982600
Epoch 150 of 200 took 0.572337s
   val loss: 0.059506
   val acc: 0.983400
Epoch 155 of 200 took 0.567339s
   val loss: 0.058481
   val acc: 0.983700
Epoch 160 of 200 took 0.570569s
   val loss: 0.058500
   val acc: 0.983600
Epoch 165 of 200 took 0.570399s
   val loss: 0.056760
   val acc: 0.983600
Epoch 170 of 200 took 0.574436s
   val loss: 0.057231
   val acc: 0.984000
Epoch 175 of 200 took 0.552374s
   val loss: 0.056794
   val acc: 0.984000
Epoch 180 of 200 took 0.562672s
   val loss: 0.056608
   val acc: 0.984000
Epoch 185 of 200 took 0.564349s
   val loss: 0.055433
   val acc: 0.984100
Epoch 190 of 200 took 0.573892s
   val loss: 0.056283
   val acc: 0.983900
Epoch 195 of 200 took 0.562397s
   val loss: 0.054887
   val acc: 0.984400
Epoch 200 of 200 took 0.571549s
   val loss: 0.055525
   val acc: 0.984400
Total training time: 116.670947

Start testing the network ...
   test loss: 0.049633
   test acc: 0.985300
Model is saved to: model.npz
