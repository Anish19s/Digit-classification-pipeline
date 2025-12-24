# Digit-classification-pipeline
This project implements a Convolutional Neural Network (CNN) from scratch in PyTorch to classify handwritten digits from the MNIST dataset.
The model learns spatial features using convolutional layers and achieves strong accuracy with minimal training.

📌 Features

1)CNN built from scratch (no prebuilt models)
2)Trained and evaluated on the MNIST dataset
3)Supports GPU acceleration (CUDA) if available
4)Efficient data loading with batching and multiprocessing
5)Includes a helper function for single-digit prediction

⚙️ Tech Stack

1)Python
2)NumPy
3)PyTorch
4)Torchvision


🚀 Training Details

1)Dataset: MNIST
2)Loss Function: CrossEntropyLoss
3)Optimizer: Adam
4)Batch Size: 128
5)Epochs: 3
6)Device: CPU / GPU (auto-detected)

📊 Results

1)Achieves ~98% accuracy on the MNIST test dataset after a few epochs.
2)Demonstrates effective feature extraction using convolutional layers.
