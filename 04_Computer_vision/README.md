# Introduction to CNN with Keras (MNIST Digit Recognizer)

This repository contains a Jupyter Notebook demonstrating how to build, train, and evaluate a Convolutional Neural Network (CNN) using Keras and TensorFlow. The model is trained on the classic MNIST dataset to classify handwritten digits (0-9).

## Overview
The goal of this project is to accurately recognize handwritten digits. It includes data preprocessing, image data augmentation, model building, and generating a submission file (formatted for the Kaggle Digit Recognizer competition).

## Features
* **Data Visualization:** Exploratory data analysis using Matplotlib and Seaborn.
* **Data Preprocessing:** Normalization and reshaping of image arrays.
* **Data Augmentation:** Utilizing Keras `ImageDataGenerator` to prevent overfitting by artificially expanding the training dataset.
* **CNN Architecture:** A Sequential model utilizing `Conv2D`, `MaxPool2D`, `Flatten`, `Dense`, and `Dropout` layers.
* **Learning Rate Annealing:** Using `ReduceLROnPlateau` to dynamically reduce the learning rate when a metric has stopped improving.

## Dependencies
To run this notebook, you will need the following libraries installed:
* `pandas`
* `numpy`
* `matplotlib`
* `seaborn`
* `scikit-learn`
* `tensorflow` (Keras is included within TensorFlow)

You can install these dependencies via pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow


How to Run
1. Clone this repository to your local machine.

2. Ensure you have the required datasets (train.csv and test.csv) downloaded and placed in the appropriate directory (e.g., from the Kaggle Digit Recognizer competition).

3. Open the Jupyter Notebook:
   jupyter notebook "introduction to CNN Keras.ipynb"

4. Run the cells sequentially to train the model and generate predictions.

Results
The notebook ultimately predicts the labels for the test dataset and outputs a file named cnn_mnist_datagen.csv.
This file contains the ImageId and predicted Label for each test image, ready for submission or further evaluation.
