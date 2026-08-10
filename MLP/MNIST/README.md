MNIST Digit Classification  — PyTorch
This repository contains two separate implementations for handwritten digit classification on the MNIST dataset using PyTorch:

MLP (Multilayer Perceptron) model

model includes:

Full training pipeline
Evaluation on the MNIST test set
Loss visualization
Inference on custom external images (PNG files included in the repository)
Note: The MNIST dataset is not included in this repository.
PyTorch automatically downloads it when running the notebooks.

Models Included
MLP Model
A simple fully-connected neural network trained on flattened 28×28 MNIST images.

Features:

1 hidden layer
ReLU activation
CrossEntropyLoss
Adam optimizer
Training loss visualization
Test accuracy evaluation


##License: This project is intended for educational and research purposes.

Dataset Handling
You do not need to download MNIST manually.

PyTorch automatically downloads the dataset when running:

datasets.MNIST(root='data', train=True, download=True)
