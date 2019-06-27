# Pothole_detection_with_Convolutional_neural_networks

### This project trains a CNN to perform binary classification to classify images into potholes vs non-potholes. Originally I trained a Mobilenet-SSD that would extract regions of distress from live footages of Highway roads taken from a camera mounted on top of a car. These distress regions are then fed to the CNN trained in this project, which would then classsify the distress regions into pothole or not a pothole.

### The training dataset for this network consists of 15492 Images( 7746 of each class). I am only sharing some sample data images. After training we reach a max training accuracy of 98.4% and test accuracy of 96.2%.


Programming Language: Python.
Software tools and libraries: Keras, Tensorflow, Opencv, Numpy, Sci-kit learn.
Training Hardware: 12-core I7, 16GB RAM, Nvidia GeForce RTX 2080 Ti 11GB.
Deployement Hardware: I5, 8GB RAM, 2GB Nvidia Graphics.
