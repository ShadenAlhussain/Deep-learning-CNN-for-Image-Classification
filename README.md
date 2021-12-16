# Convolutional Neural Networks for Image Classification

## Abstract
Recognizing photos is one of the most common problems, and it is also important in image search engines such as Google or AliExpress where the user uses image contents to query for similar things.
The goal of this project is to build a deep learning model that can recognize objects in images and predict the class of the image. 


## Design
The project is based on CNN model, I will build a convolution neural network in Keras on a CIFAR-10 dataset, which consists of 60,000 with the size of 32 by 32 pixels color images in 10 classes.

## Data
CIFAR-10 dataset consists of 60,000 32x32 pixels color images in 10 classes. The 10 different classes represent airplanes, cars, birds, cats, deer, dogs, frogs, horses, ships, and trucks, in which each of those classes consists of 6000 images.
CIFAR-10 dataset is already available in the datasets module of Keras you can directly import it from keras.dataset or download it from  https://www.cs.toronto.edu/~kriz/cifar.html

## Algorithms

The Training dataset consists of 50,000 32X32 color images of 10 different objects.

•	Convert the pixel values of the dataset to float type.
•	Create the sequential model and add the layers (Convolution layer, batchNormalization layer, pooling layer, dropout layer, flattening layer and Dense Layers) 
•	Fit and evaluate the model 

## Tools
•	NumPy for data manipulation.
•	TensorFlow, Keras, Scikit-learn for modeling.
•	Matplotlib for visualizations.

