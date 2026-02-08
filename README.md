# Neural Network Implementation from Scratch

This project implements a fully connected neural network from scratch using only NumPy. It demonstrates the fundamental concepts of neural networks—forward propagation, backpropagation, activation functions, and gradient descent—without relying on high-level deep learning frameworks.

## Features
- **Custom Layers**: Fully connected layer, activation layer (ReLU), flatten layer
- **Manual Backpropagation**: Implements gradient computation and weight updates
- **Training Loop**: Mini-batch gradient descent with configurable epochs and learning rate
- **Evaluation**: Uses Sum of Squared Errors (SSE) and R² score
- **Dataset**: California Housing dataset for regression task

## Advantages & Disadvantages of ReLU
- **Advantages**
Computationally efficient – Simple max operation

Avoids vanishing gradient – Gradient is constant for positive inputs

- **Disadvantages**
Dying ReLU problem – Neurons can become inactive

Sensitive to initialization – Poor initialization can lead to dead neurons
