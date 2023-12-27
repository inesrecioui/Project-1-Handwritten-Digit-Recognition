# MNIST Neural Network Models

This repository contains Python code implementing and comparing different neural network architectures on the MNIST dataset using PyTorch.

## Overview

The purpose of this project is to demonstrate and compare the performance of three different neural network architectures for handwritten digit classification using the popular MNIST dataset.

The models implemented are:
1. **Simple Neural Network (NN)**
2. **Complex Neural Network**
3. **Neural Network with Dropout**

## Project Structure

- **`models.py`:** Contains the definitions of the neural network models using PyTorch.
- **`train.py`:** Code to train and evaluate the models on the MNIST dataset.
- **`requirements.txt`:** List of required Python libraries for reproducing the environment.
- **`README.md`:** Project overview, instructions, and observations.

## Usage

### Environment Setup
1. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   
## Training and Evaluation
- Run train.py to train and evaluate all three models on the MNIST dataset. This script includes training loops, prints test accuracy, and plots training and test losses.

## Observations
1. Model Complexity: Observe differences in performance and training time between the simple and complex neural networks.
2. Overfitting: Analyze training and test loss graphs to identify potential overfitting issues.
3. Dropout Effect: Evaluate the impact of dropout layers on model performance.

## Results
The project generates graphs illustrating the training and test losses for each model. Users can interpret these results to compare the models' performance in terms of accuracy, training time, and resistance to overfitting.
