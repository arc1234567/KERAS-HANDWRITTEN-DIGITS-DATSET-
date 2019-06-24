# KERAS-HANDWRITTEN-DIGITS-DATSET-
MNIST database of handwritten digits
Dataset of 60,000 28x28 grayscale images of the 10 digits, along with a test set of 10,000 images.
Usage:
from keras.datasets import mnist

(x_train, y_train), (x_test, y_test) = mnist.load_data()
Returns:

2 tuples:
x_train, x_test: uint8 array of grayscale image data with shape (num_samples, 28, 28).
y_train, y_test: uint8 array of digit labels (integers in range 0-9) with shape (num_samples,).
Arguments:

path: if you do not have the index file locally (at '~/.keras/datasets/' + path), it will be downloaded to this location.
