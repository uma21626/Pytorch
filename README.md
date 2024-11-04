# Pytorch
# MNIST Handwritten Digit Classification with PyTorch

This project implements a simple feedforward neural network using PyTorch to classify handwritten digits from the MNIST dataset.

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Training the Model](#training-the-model)
- [Evaluation](#evaluation)
- [License](#license)

## Introduction

The MNIST dataset is a well-known dataset in the machine learning community, consisting of 70,000 grayscale images of handwritten digits (0-9). This project demonstrates how to build, train, and evaluate a neural network using PyTorch to classify these images.

## Requirements

- Python 3.6 or higher
- PyTorch
- torchvision

## Installation

You can install the required libraries using pip. Run the following command in your terminal:
pip install torch torchvision

## Training the Model
The model is trained using the following parameters:

Number of Epochs: 5
Batch Size: 64
Optimizer: Adam
Loss Function: CrossEntropyLoss

## Evaluation
After training, the model is evaluated on the test dataset. The accuracy of the model is printed to the console.
