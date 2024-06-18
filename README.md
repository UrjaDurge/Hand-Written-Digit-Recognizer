
# Handwritten Digit Recognizer

Overview

This project focuses on building a handwritten digit recognizer using deep learning. The goal is to classify images of handwritten digits (0-9) accurately.

Dataset

The dataset used for this project is the MNIST dataset, which is available as part of TensorFlow's datasets. The MNIST dataset consists of 60,000 training images and 10,000 test images of handwritten digits, 0 through 9.

Requirements

To run the code, you need the following libraries:

tensorflow

keras

numpy

matplotlib

Model

For this project, a deep learning model is built using the Keras Sequential API. The model consists of the following layers:

Input Layer: Flatten layer to convert 28x28 images into a 1D array.

Hidden Layers: Dense layers with ReLU activation function.

Output Layer: Dense layer with 10 neurons (one for each digit) and softmax activation function.

Files

digit_recognizer.ipynb: Jupyter notebook containing the code for data loading, model building, training, and evaluation, train datset, test dataset
README.md: This file.

Usage

Clone this repository.

Open and run the notebook digit_recognizer.ipynb in Jupyter Notebook or Jupyter Lab.

Follow the instructions in the notebook to load the data, build the model, train it, and evaluate its performance.

You can also use the trained model to make predictions on new handwritten digit images.

Results

The model achieves an accuracy of approximately 97% on the test data.

