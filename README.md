#### Update [05/12/2019]: The current file structure is quite hard to navigate and find where each topic is. I am working to make this simpler. I'll link each of the contains with the corresponding file soon.


**Tensorflow Version 2.x is used throughout the repo.**

This repo is collection of my understanding and experiments with tf.keras - Sequential API.

It also involves mathematical foundations of tensor operations and how CNNs work.

### Contains:
- Tensors and Tensor operations using Numpy :  || [Colab](https://colab.research.google.com/github/dhruvilmaniar/PracticalTF/blob/master/TensorOperations.ipynb) || [Github](../blob/master/TensorOperations.ipynb)

- Loading data to tensorflow
  - Involves loading Tensors, arrays, images, time-series, and textual data.
  
- Activation functions using Numpy and Matplotlib : || [Colab](https://colab.research.google.com/github/dhruvilmaniar/PracticalTF/blob/master/ActivationFuncMath.ipynb) || [Github](../blob/master/ActivationFuncMath.ipynb)
  - Involves ReLU, Sigmoid with graphical understanding
  
- Defining custom activation functions

- Playing with MNIST and Fashion MNIST, IRIS, Titanic dataset. || [Colab](https://colab.research.google.com/github/dhruvilmaniar/PracticalTF/blob/master/TFSelf.ipynb) || [Github](../blob/master/TFSelf.ipynb)

- Using *Pre-defined layers* like `Dense`, `Conv2D`, `Flatten`, `Dropout`, `Max-pooling`, `Average-Pooling` etc.

- Using Pre-defined feature extractors as `ResNet`, `DeepLab`, `Inception-v2`, `VGG-16` etc.

- Defining *custom layers* in tf.keras API || [Colab](https://colab.research.google.com/github/dhruvilmaniar/PracticalTF/blob/master/CustomModel2.ipynb) || [Github](../blob/master/CustomModel2.ipynb)

- GPU Acceleration in tensorflow || [Colab](https://colab.research.google.com/github/dhruvilmaniar/PracticalTF/blob/master/GPUvsCPU_Acceleration.ipynb) || [Github](../blob/master/GPUvsCPU_Acceleration.ipynb)

- *Distributed learning* using `Mirrored strategy`, `Multiworker Mirrored Strategy`, `Parameter server strategy` using *`tf.distribute.Strategy`* API.
