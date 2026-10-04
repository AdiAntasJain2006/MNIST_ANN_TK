# MNIST Digit Classification using Neural Network

A handwritten digit classification project built using **TensorFlow and Keras**. The project trains a fully connected neural network to classify grayscale MNIST digit images into 10 classes (0–9).

## Overview

The model processes 28×28 grayscale digit images represented as 784 pixel features and learns to classify them into one of 10 digit classes.

The project covers:

- Dataset loading and preprocessing
- Feature and label separation
- Neural network architecture design
- Model training and validation
- Prediction using the trained model
- Classification report and accuracy evaluation
- Training and validation performance visualization

## Dataset

The project uses the MNIST handwritten digit dataset.

- Training data: `mnist_train_small.csv`
- Image size: **28 × 28 pixels**
- Input features: **784 pixels**
- Number of classes: **10 (0–9)**
- Training samples: **19,999**
- Validation split: **20%**

Each sample contains one digit label followed by 784 pixel values.

## Model Architecture

The project uses a fully connected neural network implemented with TensorFlow/Keras.

```text
Input
784 Pixel Features
      │
      ▼
Dense Layer
64 Neurons
      │
      ▼
Dense Layer
32 Neurons
      │
      ▼
Dense Layer
15 Neurons
      │
      ▼
Output Layer
10 Classes
      │
      ▼
Predicted Digit
