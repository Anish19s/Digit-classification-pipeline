Digit Classification using Convolutional Neural Networks (PyTorch)
📌 Overview

This project is an introductory implementation of a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset.
The goal of this project was to understand the fundamentals of neural networks and CNNs, including how convolution layers work, how models are trained in PyTorch, and how performance is evaluated.

This project was built as a learning-focused deep learning pipeline, not as a production-level system.

🧠 Problem Statement

Handwritten digit recognition is a classic computer vision problem where the task is to correctly classify grayscale images of digits (0–9).

The MNIST dataset contains:
-60,000 training images
-10,000 test images
-Each image is 28×28 pixels in grayscale

🏗️ Model Architecture

The model is a simple Convolutional Neural Network (CNN) consisting of:
-Convolutional layers for feature extraction
-ReLU activation functions
-Pooling layers for dimensionality reduction
-Fully connected layers for classification

CNNs are used instead of traditional fully connected networks because they are better at capturing spatial patterns in images.

⚙️ Training Pipeline

The training pipeline includes:

-Loading and preprocessing the MNIST dataset
-Forward pass through the CNN
-Loss computation using Cross Entropy Loss
-Backpropagation and parameter updates using Adam optimizer
-Model evaluation on a held-out test set

GPU acceleration is supported if available.

📊 Results

-Achieved approximately 98% accuracy on the MNIST test dataset
-Demonstrates effective learning of spatial features using CNNs
-This accuracy is reasonable for a beginner-level CNN without heavy tuning or advanced architectures.

📚 What I Learned

Through this project, I learned:

-How convolution and pooling layers extract features from images
-Why CNNs perform better than fully connected networks for image data
-How to implement a training loop in PyTorch
-The role of loss functions, optimizers, and backpropagation
-Basics of model evaluation and overfitting

🛠️ Technologies Used

-Python
-PyTorch
-Torchvision
-NumPy
-Matplotlib


