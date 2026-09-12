# Fashion-MNIST Classification with PyTorch

A simple **Artificial Neural Network (ANN)** built using PyTorch to classify Fashion-MNIST images into 10 clothing categories.

## What This Project Covers

- Loading and preprocessing the dataset
- Creating a custom PyTorch `Dataset`
- Using `DataLoader` for mini-batch training
- Building an ANN using `nn.Module` and `nn.Sequential`
- Training the model using mini-batch gradient descent
- Evaluating the model on the test set

## Model Architecture

```text
784 → 128 → ReLU → 64 → ReLU → 10

Dataset link : https://www.kaggle.com/datasets/zalando-research/fashionmnist
