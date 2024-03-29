# Advanced Machine Learning Course Assignments
Collection of assignments performed during the Advanced Machine Learning course.

## Assignment 1
The assignment consists in the prediction of the price (same name as the target variable in the dataset) of a private room/entire apartment using a neural network.
The dataset includes all the information you need to learn more about hosts, geographic availability, and necessary metrics of Airbnb apartments in New York City in 2019.
The provided data comprises the training set that can be used for the training (and eventually for the validation) and the unlabelled test set.

## Assignment 2
The assignment consists in the prediction of default payments using a neural network.
The dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.
The provided data comprises the training set that can be used for the training (and eventually for the validation) and the unlabelled test set.

## Assignment 3
The task of the assignment #3 is the design of a CNN architecture and its training.

Input dataset: MNIST digits (input size 28x28x1, number of classes: 10).
The dataset is not distributed since can be easily downloaded directly from Keras.

The CNN has to be designed with the aim of reaching the maximum possible accuracy on the test set, with the hard constraint of a maximum of 7K learnable parameters.

## Assignment 4
The task of the assignment #4 is Transfer Learning using a CNN pretrained on IMAGENET. The suggested architecture is the VGG16.
The CNN should be used as fixed feature extractor on a new task of your choice containing a number of classes in the range from 2 to 10.

### Task: Food Classification
The dataset is the Food-5K dataset available on [EPFL - Food Image Dataset](https://www.epfl.ch/labs/mmspg/downloads/food-image-datasets/) and contains 2500 food and 2500 non-food images.
The task is to train a DL model to recognize whether the given image contains any kind of food (class=`FOOD`) or not (class=`NON_FOOD`).
