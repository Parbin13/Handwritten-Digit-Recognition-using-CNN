# Handwritten Digit Recognition using CNN

This repository contains a convolutional neural network (CNN) model developed as a university project to recognize handwritten digits. The project uses the MNIST dataset for training and testing, achieving high accuracy in digit recognition.

## Project Overview
This project implements a CNN model in Python using Keras and TensorFlow, designed to classify handwritten digits (0-9) from grayscale images. The CNN model extracts essential features of the digits through convolutional and pooling layers, followed by dense layers for classification.

## Model Architecture
- **Input Shape**: 28x28 grayscale images
- **Layers**:
  - 3 Convolutional Layers with Max Pooling
  - Dropout Layer to reduce overfitting
  - 2 Dense Layers for digit classification
- **Total Parameters**: Approximately 390,000

### Training Performance
- **Epochs**: 15
- **Accuracy**: 99.37% on test data
- **Loss**: 0.0217

## Setup Instructions

### Prerequisites
- Python 3.x
- TensorFlow and Keras libraries
- MNIST dataset (automatically downloaded by Keras)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Parbin13/Handwritten_Digit_Recognition_CNN.git

  
