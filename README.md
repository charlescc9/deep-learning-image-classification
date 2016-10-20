# SVHN
SVHN is an image classification project aimed to solve the problem of classifying digit sequences in images using the Street View House Number dataset ([SVHN] (http://ufldl.stanford.edu/housenumbers/)). It presents a clear solution using TensorFlow to create deep and convolutional neural networks. It is also being used as the capstone project for Udacity's Machine Learning Engineer Nanodegree.

## Software Dependencies
SVHN is written in Python 2.7 in a Jupyter notebook and uses several common software libraries, most notably TensorFlow. In order to run it, you  must install the follow dependecies:
* [Jupyter] (http://jupyter.org/)
* [TensorFlow] (https://www.tensorflow.org/)
* [Numpy] (http://www.numpy.org/)
* [scikit-learn] (http://scikit-learn.org/)
* [Python Imaging Library] ()http://www.pythonware.com/products/pil/
* [h5py] (http://www.h5py.org/)
* [matplotlib] (http://matplotlib.org/)

## Data
The [SVHN] (http://ufldl.stanford.edu/housenumbers/) dataset is publically available and comes in two forms, the original images of house number with multiple digits, and cropped images that only contain one digit apiece. This project uses the former dataset, as it represents the real world problem. In order to run the project, you must download the data and place it in the directory referenced in the first cell of the code.

## Computational Requirements
As SVHN trains a fairly deep convolutional neural network on a large amount of data, running it takes considerable computational resources. This is an unavoidable necessity when attempting to create deep learning models that perform well. If one does not have a powerful enough personal computer, one of two things may be done: either the number of epochs to train the model can be decreased, or one can run it on a more powerful cloud instance. The author used a Amazon Web Services instance with GPU support.

## Accompanying Report
As this project is educational in nature, there is also an accompanying report pdf (TODO) that thouroughly explains the project implementation as well as discussing its place in the deep learning field.

## Background
This project assumes that the user has a basic understanding of machine learning principles and technics. There are also a number of specific resources that the author used:
* [TensorFlow tutorials] (https://www.tensorflow.org/versions/r0.11/tutorials/index.html)
* [Udacity deep learning course] (https://www.udacity.com/course/deep-learning--ud730)
* [Stanford CNN course] (http://cs231n.stanford.edu/)

### License
This project uses the [MIT License] (https://github.com/charlescc9/svhn/blob/master/LICENSE).
