MNIST Digit Classification  — PyTorch
This repository contains two separate implementations for handwritten digit classification on the MNIST dataset using PyTorch:


CNN (Convolutional Neural Network) model
model includes:

Full training pipeline
Evaluation on the MNIST test set
Loss visualization
Inference on custom external images (PNG files included in the repository)
Note: The MNIST dataset is not included in this repository.
PyTorch automatically downloads it when running the notebooks.

Model Included

A convolutional neural network trained on MNIST images with spatial structure preserved.

Features:

Convolution + MaxPool layers
ReLU activation
Fully connected classifier
Training loss visualization
Test accuracy evaluation
Inference on external images (1.png, 3.png, 5.png)
##Requirements: Python 3.x PyTorch torchvision matplotlib PIL (Pillow)

##License: This project is intended for educational and research purposes.

Dataset Handling
You do not need to download MNIST manually.

PyTorch automatically downloads the dataset when running:

datasets.MNIST(root='data', train=True, download=True)
