# SVHN
SVHN is an image classification project aimed to solve the problem of classifying digit sequences in images using the Street View House Number dataset (SVHN). It presents a clear solution using TensorFlow to create deep and convolutional neural networks. It is also being used as the capstone project for Udacity's Machine Learning Engineer Nanodegree.

## Software Dependencies
SVHN is written in Python 2.7 in a Jupyter notebook and uses several common software libraries, most notably TensorFlow. In order to run it, you  must install the follow dependecies:
[Jupyter] (http://jupyter.org/)
TensorFlow
Numpy
Sklearn
PIL
h5py
matplotlib

## Data
The SVHN dataset is publically available and comes in two forms, the original images of house number with multiple images, and a cropped images that only contain one digit apiece. This project uses the former dataset, as it represents the real world problem. In order to run the project, you must download the data and place it in a directory that is references in the first cell of the code.

## Computational Requirements
As SVHN trains a fairly deep convolutional neural network on a large amount of data, running it takes considerable computation resources. This is an unavoidable necessity when attempting to create deep learning models that perform well. If one does not have a powerful enough personal computer, one of two things may be done: either the number of epochs to train the model can be decreased, or one can run it in a more powerful cloud instance. Amazon Web Services offers many instance types that work well, especially to run on GPUs.

## Accompanying Report
As this project is educational in nature, there is also an accompanying report pdf (TODO) that thouroughly explains the project implementation as well as discussing its place in the deep learning field.

## Background
This project assumes that the user has a basic understanding of machine learning principles and technics. There are many excellent tutorials one can use to get up to speed on these concepts. 

### License
This project uses the MIT License.
