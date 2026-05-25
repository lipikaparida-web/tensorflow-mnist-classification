## Handwritten Digit Classification — TensorFlow & Keras (MNIST)

### Overview
An ANN-based image classification model built with TensorFlow/Keras to classify handwritten digits (0–9) from the MNIST dataset. Achieves 97.49% test accuracy.

### Model Architecture
Input (784,)  →  Dense(3000, ReLU)  →  Dense(1000, ReLU)  →  Dense(500, ReLU)  →  Dense(10, Softmax)

Optimizer: Adam
Loss: Sparse Categorical Crossentropy
Epochs: 2
Test Accuracy: 97.49%


### Dataset

MNIST — 60,000 training images, 10,000 test images
28×28 grayscale images, flattened to 784-dimensional vectors
Pixel values normalized to [0, 1]


### Results
MetricValueTest Accuracy97.49%Test Loss0.0796

### Tech Stack

Python, TensorFlow 2.x, Keras
NumPy, Matplotlib
Google Colab


### Files
├── tensorflow_mnist.ipynb    # Full notebook with training and evaluation
└── README.md

## Part of my data science portfolio.
