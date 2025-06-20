# Project 2 – Cost Functions and Regularization (MNIST)

This project extends the basic MNIST neural network by experimenting with different cost functions, regularization techniques, and activation functions.

## Part A: Softmax + Log-Likelihood
- Implements a `LogLikelihoodCost` class and `softmax(z)` function.
- Applies softmax to the output layer only.
- Demonstrates improved or equivalent performance.

## Part B: L1 Regularization
- Replaces L2 regularization with L1.
- Keeps λ the same to isolate impact of regularization type.

## Part C: Tanh Activation
- Replaces sigmoid with `tanh(z)` in hidden layers only.
- Keeps sigmoid in the output layer.
- Tests if performance improves with smoother gradient behavior.

##  Files
- `prj2a.ipynb` – Part A
- `prj2b.ipynb` – Part B
- `prj2c.ipynb` – Part C
- `newnetwork2.ipynb` – Base model
- `mnist.pkl.gz` – Dataset file (required)

##  How to Run
Run each notebook individually in Jupyter. Make sure `mnist.pkl.gz` is in the same directory.
