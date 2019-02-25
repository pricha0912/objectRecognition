# objectRecognition

In this project, deployed a convolutional neural network (CNN) for object recognition. 

Please refer:
https://arxiv.org/pdf/1412.6806.pdf

Built this model using Keras, a high-level neural network application programming interface (API) that supports both Theano and Tensorflow backends. You can use either backend; however, I will be using Theano.

Steps:

Import datasets from Keras
Use one-hot vectors for categorical labels
Addlayers to a Keras model
Load pre-trained weights
Make predictions using a trained Keras model
The dataset we will be using is the CIFAR-10 dataset, which consists of 60,000 32x32 color images in 10 classes, with 6000 images per class. There are 50000 training images and 10000 test images.

Dataset : https://www.cs.toronto.edu/~kriz/cifar.html
