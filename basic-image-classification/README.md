# About

## Basic Image Classification

1. This project trains a neural network model to classify images of clothing, like sneakers and shirts. It uses the Fashion MNIST dataset which contains 70,000 grayscale images in 10 categories. Fashion MNIST is intended as a drop-in replacement for the [Classic MNIST](https://www.tensorflow.org/datasets/catalog/mnist) dataset—often used as the "Hello, World" of machine learning programs for computer vision.

2. I have used Fashion MNIST for variety, and because it's a slightly more challenging problem than regular MNIST. Both datasets are relatively small and are used to verify that an algorithm works as expected. They're good starting points to test and debug code.

3. Here, 60,000 images are used to train the network and 10,000 images to evaluate how accurately the network learned to classify images.

## Advance Image Classification

This project contains solution of another classification problem where we use convolutional neural network (CNN) to classify images of various types of flowers. We show concepts like data augmentation and dropout to mitigate over-fitting. We will also see how to efficiently loading a dataset off disk using tensorflow.

## Data Augmentation

This project demonstrates data augmentation: a technique to increase the diversity of your training set by applying random (but realistic) transformations, such as image rotation. We will use the Keras preprocessing layers and ```tf.image``` methods

## Acknowledgment

1. Beginner Tutorial named as [Basic Image Classification](https://www.tensorflow.org/tutorials/keras/classification) at tensorflow website.
2. [Image Classification](https://www.tensorflow.org/tutorials/images/classification) tutorial.
3. [Data Augmentation](https://www.tensorflow.org/tutorials/images/data_augmentation)
 tutorial.