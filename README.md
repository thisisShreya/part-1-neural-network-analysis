# part-1-neural-network-analysis

# Neural Network Fundamentals and Training Behavior Analysis

## Project Objective

The objective of this project is to build and analyze a feed-forward neural network model using a supervised learning dataset.

## Dataset Description

The dataset contains multiple input features and one target variable called Churn. The goal is to predict customer churn using neural networks.

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- tensorflow

## Data Preprocessing

- Checked missing values
- Encoded categorical features
- Scaled numerical data
- Split dataset into training and testing sets

## Neural Network Architecture

- Input Layer
- Hidden Layer with ReLU activation
- Output Layer with Sigmoid activation

## Loss Function

Binary Crossentropy

## Optimizer

Adam Optimizer

## Evaluation Metrics

- Accuracy
- Confusion Matrix
- Classification Report

## Hyperparameter Experiments

Three experiments were performed by changing:
- Number of neurons
- Number of hidden layers
- Learning rate
- Activation functions

## Final Reflection

Weights and biases help the neural network learn patterns from data.

Activation functions introduce non-linearity and help the network learn complex relationships.

A high learning rate causes unstable training while a very low learning rate slows down learning.

The model showed reasonable generalization with no major overfitting issues.

## Dataset Source

Dataset provided in assignment Google Drive link.(https://drive.google.com/drive/folders/1akV6po4Nrgkc3yQrJkzA6cJlV-wBvUYs?usp=sharing)
