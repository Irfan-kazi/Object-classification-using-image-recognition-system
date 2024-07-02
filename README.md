Object-classification-using-image-recognition-system
A convolutional neural network (CNN) will be used in this project to recognize objects. In particular, the All-CNN network described in the 2015 ICLR paper "Striving For Simplicity: The All Convolutional Net" will be employed. This paper is available at this link:

A PDF of 1412.6806 can be found at arxiv.org.

Using the CIFAR-10 picture dataset, this convolutional neural network achieved state-of-the-art performance in object detection in 2015. Keras is a high-level neural network application programming interface (API) that supports Tensorflow and Theano backends, and it will be used to build this model. You are welcome to use either backend, but I'll be using Theano.

With this project, we'll discover how to:

Dataset import from Keras
For categorical labeling, use one-hot vectors.
Layer additions in a Keras model
Put pre-trained weights on.

Utilizing a trained Keras model, make predictions
The CIFAR-10 dataset, which has 60,000 32x32 color photos divided into 10 classes with 6000 photos in each class, is the one we'll be using. A total of 50,000 training and 10,000 test photos are available.

