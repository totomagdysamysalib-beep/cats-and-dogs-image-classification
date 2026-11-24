# Cats and Dogs Image Classification 🐱🐶

## Overview
This project uses **PyTorch** to build and train a Convolutional Neural Network (CNN) that classifies images of cats and dogs.

The model is inspired by the TinyVGG architecture and is trained on a balanced subset of the Microsoft Cats vs Dogs dataset.

## Project Features
- Downloading the dataset using KaggleHub
- Filtering corrupted images
- Data preprocessing and augmentation
- Building a custom CNN using PyTorch
- Training and evaluating the model
- Visualizing training and testing loss and accuracy
- Predicting the class of a new image using its URL

## Model Architecture
The model consists of:
- Two convolutional blocks
- Convolutional layers with ReLU activation
- Max Pooling layers
- A fully connected classification layer

**Input image size:** 64 × 64 RGB  
**Output classes:** Cat and Dog

## Technologies Used
- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Scikit-learn
- PIL (Pillow)
- KaggleHub

## Dataset
Microsoft Cats vs Dogs Dataset

The project uses a balanced subset of 10,000 images, with 5,000 images from each class.

The dataset is split into training and testing sets using an 80/20 split.

## Training
The model is trained using:
- CrossEntropyLoss
- Adam Optimizer
- Learning rate: 0.001
- Batch size: 32
- 30 epochs

## Results
The project tracks and visualizes:
- Training Loss
- Testing Loss
- Training Accuracy
- Testing Accuracy

## Prediction
The trained model can classify a new image provided through an image URL.

## Learning Objectives
This project helped me practice:
- Building CNNs from scratch
- Working with image datasets
- Understanding DataLoaders and batching
- Applying data augmentation and normalization
- Training and evaluating deep learning models
- Making predictions on unseen images


