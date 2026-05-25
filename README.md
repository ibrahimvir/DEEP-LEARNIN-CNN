# DEEP-LEARNIN-CNN
# Handwritten Digit Recognition using CNN

## Project Overview

This project is a Deep Learning based Handwritten Digit Recognition System developed using Convolutional Neural Networks (CNN) and the MNIST dataset.

The model is trained to recognize handwritten digits from 0 to 9 with high accuracy.

---

## Features

* CNN-based image classification
* Handwritten digit prediction
* MNIST dataset implementation
* Deep learning model training
* Image preprocessing
* Model evaluation and accuracy analysis
* Interactive prediction interface

---

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Google Colab

---

## Deep Learning Concepts Used

* Neural Networks

* Convolutional Neural Networks (CNN)

* Activation Functions

* ReLU
  f(x)=\max(0,x)

* Softmax
  \sigma(z_i)=\frac{e^{z_i}}{\sum_{j=1}^{K}e^{z_j}}

* Dropout Regularization

* Adam Optimizer

* Categorical Crossentropy Loss

---

## Dataset

MNIST Handwritten Digits Dataset

Loaded using:

```python
from tensorflow.keras.datasets import mnist
```

---

## Model Architecture

* Conv2D
* MaxPooling2D
* Flatten
* Dense Layers
* Dropout Layer
* Output Layer

---

## Results

The CNN model successfully predicts handwritten digits with high accuracy.

---

## Future Improvements

* Deploy full web application
* Add drawing canvas input
* Improve UI design
* Train on custom handwritten datasets

---

## Author

Deep Learning Final Project
