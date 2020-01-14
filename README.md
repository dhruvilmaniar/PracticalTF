#### Update [05/12/2019]: The current file structure is quite hard to navigate and find where each topic is. I am working to make this simpler. I'll link each of the contains with the corresponding file soon.


**Tensorflow Version 2.x is used throughout the repo.**

This repo is collection of my understanding and experiments with tf.keras - Sequential API.

It also involves mathematical foundations of tensor operations and how CNNs work.

### Contains:
- Tensors and Tensor operations using Numpy : [Colab][1] [Github][2]

- Loading data to tensorflow
  - Involves loading Tensors, arrays, images, time-series, and textual data.
  
- Activation functions using Numpy and Matplotlib  [Colab][3] [Github][4]
  - Involves ReLU, Sigmoid with graphical understanding
  
- Defining custom activation functions

- Playing with MNIST and Fashion MNIST, IRIS, Titanic dataset.

- Using *Pre-defined layers* like `Dense`, `Conv2D`, `Flatten`, `Dropout`, `Max-pooling`, `Average-Pooling` etc.

- Using Pre-defined feature extractors as `ResNet`, `DeepLab`, `Inception-v2`, `VGG-16` etc.

- Defining *custom layers* in tf.keras API

- GPU Acceleration in tensorflow

- *Distributed learning* using `Mirrored strategy`, `Multiworker Mirrored Strategy`, `Parameter server strategy` using *`tf.distribute.Strategy`* API.

[1] : https://colab.research.google.com/github/dhruvilmaniar/PracticalTF/blob/master/TensorOperations.ipynb
[2] : https://github.com/dhruvilmaniar/PracticalTF/blob/master/TensorOperations.ipynb
[3] : https://colab.research.google.com/github/dhruvilmaniar/PracticalTF/blob/master/ActivationFuncMath.ipynb
[4] : https://github.com/dhruvilmaniar/PracticalTF/blob/master/ActivationFuncMath.ipynb
