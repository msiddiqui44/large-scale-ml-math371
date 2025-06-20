# Project 3 – Deep CNNs on CIFAR-10

This project upgrades neural network models to convolutional neural networks (CNNs) using the CIFAR-10 image dataset and PyTorch.

## Part A: ReLU Activation
- Modifies hidden layers to use `ReLU` instead of `sigmoid`.
- Keeps `sigmoid` in the output layer.
- Aims to improve learning speed and model accuracy.

## Part B: Confusion Matrix
- Generates a 10×10 confusion matrix from the test set.
- Shows per-class performance and misclassifications.

## Part C: Custom Deep CNN
- Builds a CNN with:
  - 4 convolutional layers (20 → 80 channels)
  - `AvgPool2d` after each conv layer
  - 3 fully connected layers (500 → 100 → 10)
- Uses `ELU` activation in hidden layers
- Designed to be scalable and robust.

## Files
- `prj3a.ipynb` – Part A
- `prj3b.ipynb` – Part B
- `prj3c.ipynb` – Part C

## How to Run
CIFAR-10 is automatically downloaded via `torchvision`. Run each notebook in Jupyter. Use lower epochs for testing.
