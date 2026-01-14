MishReLU: A Hybrid Activation Function for Deep Neural Networks

This repository accompanies the manuscript entitled “MishReLU: A Hybrid Activation Function for Deep Neural Networks” and provides the experimental code used to evaluate the proposed activation function.

1. Datasets

All datasets used in this study are public benchmark datasets and are automatically loaded using the standard APIs provided by TensorFlow/Keras.

The following datasets are used: MNIST/ Fashion-MNIST/ CIFAR-100


3. Models

The following neural network architectures are implemented:

A Multi-Layer Perceptron (MLP) for Fashion-MNIST

A Convolutional Neural Network (CNN) for MNIST

A ResNet-18 architecture adapted for CIFAR-100
A LSTM MODEL 
A BilSTM MODEL 

All architectures allow interchangeable activation functions to ensure fair comparisons.

4. Activation Functions

The experiments compare the proposed MishReLU activation function with commonly used baseline activation functions: ReLU/ Mish/ ELU/ LeakyReLU/ SELU

Performance is evaluated using:

Accuracy

Precision

Recall

F1-score

6. Statistical Analysis

Statistical significance between activation functions is assessed using:

The Friedman test for overall comparison
Post-hoc Wilcoxon signed-rank tests for pairwise comparisons

Post-hoc Wilcoxon signed-rank tests for pairwise comparisons

All statistical analyses are performed on results obtained from repeated runs.
