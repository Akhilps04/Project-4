# MNIST Digit Classification with Artificial Neural Network (ANN).
# Project Overview
This repository contains an implementation of a basic artificial neural network (ANN) to classify handwritten digits from the MNIST dataset. The MNIST dataset consists of 60,000 28x28 grayscale images for training and 10,000 images for testing, representing digits from 0 to 9.
The ANN model is built using TensorFlow and Keras and includes the following main steps:

# Loading and Exploring Data:

The MNIST dataset is loaded and preprocessed. Each image is a 28x28 grayscale pixel array.
Data exploration steps include checking the shapes of training and test data.
# Data Preprocessing:

The pixel values are scaled to be between 0 and 1 for faster training and improved performance.
Images are flattened into 1D arrays of 784 features for input into the ANN.
# Model Architecture:

The ANN model consists of:
An input layer with 784 neurons (flattened 28x28 images).
Hidden layers with 128, 64, and 32 neurons using ReLU and sigmoid activations.
An output layer with 10 neurons (one for each digit class) using softmax activation for multi-class classification.
Compiling and Training the Model:

The model is compiled with the Adam optimizer and sparse categorical cross-entropy loss.
Trained for 5 epochs, aiming to achieve a reasonable accuracy on the test data.
# Model Evaluation:

The model is evaluated on the test set, and a confusion matrix is generated to visualize classification performance.
Visualization:

The confusion matrix is displayed as a heatmap to analyze the prediction accuracy for each digit class.
Dependencies
numpy for mathematical operations.
tensorflow and keras for building and training the neural network.
seaborn and matplotlib for data visualization.
# How to Use
Clone the repository, install the required packages, and run the notebook to train and evaluate the model on the MNIST dataset.

# Acknowledgments
The dataset was sourced from Kaggle.
Thanks to my mentors for their guidance.

# 📄 License
This project is for academic and demonstration purposes only. Please credit the authors if reused or modified.

