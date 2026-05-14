# CIFAR-10 Image Classification using CNN (PyTorch)

This project implements a Convolutional Neural Network (CNN) using PyTorch for image classification on the CIFAR-10 dataset.

## Project Overview

The model was trained to classify images into 10 categories from the CIFAR-10 dataset using a custom CNN architecture with:

* Convolutional Layers
* Batch Normalization
* Max Pooling
* Dropout Regularization
* Data Augmentation

## Dataset

CIFAR-10 contains 60,000 color images of size 32x32 across 10 classes:

* Airplane
* Automobile
* Bird
* Cat
* Deer
* Dog
* Frog
* Horse
* Ship
* Truck

## Technologies Used

* Python
* PyTorch
* Torchvision
* NumPy
* Pandas

## Model Architecture

* 4 Convolutional Blocks
* Batch Normalization
* ReLU Activation
* MaxPooling
* Fully Connected Layers
* Dropout (0.5)

## Data Augmentation

Training images were augmented using:

* Random Rotation
* Horizontal Flip
* Normalization

## Results

| Metric              | Score  |
| ------------------- | ------ |
| Train Accuracy      | 86.23% |
| Validation Accuracy | 83.16% |
| Test Accuracy       | 81.73% |

## Key Learning Outcomes

* Building CNN architectures in PyTorch
* Training and validation pipelines
* GPU training with CUDA
* Loss calculation and accuracy tracking
* Model checkpoint saving
* Image classification workflows

## Future Improvements

* Transfer Learning (ResNet/VGG)
* Learning Rate Scheduling
* Hyperparameter Tuning
