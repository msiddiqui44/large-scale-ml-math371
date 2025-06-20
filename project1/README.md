# Project 1 – Neural Network Fundamentals (MNIST)

This project implements and experiments with a basic neural network on the MNIST dataset to explore training parameters, per-class accuracy, and training efficiency.

## 🔹 Part A: Baseline Execution
- Runs the provided `newnetwork.ipynb` code without modification.
- Confirms the environment is working and outputs are as expected.

## 🔹 Part B: Learning Rate Optimization
- Tests learning rates η = [1, 3, 5, ..., 19].
- Plots classification accuracy at epoch 29 vs. learning rate.
- Identifies the optimal learning rate.

## 🔹 Part C: Per-Digit Accuracy
- Tracks and prints classification accuracy for each digit (0–9) at every epoch.
- Helps identify which digits are easier or harder to classify.

## 🔹 Part D: SGD Speedup via Data Subsampling
- Modifies SGD to use only 1/k of the training data per epoch.
- Benchmarks runtime and final accuracy for k = 1 to 6.
- Plots accuracy vs. k and runtime vs. k.

## 📦 Files
- `prj1a.ipynb` – Part A
- `prj1b.ipynb` – Part B
- `prj1c.ipynb` – Part C
- `prj1d.ipynb` – Part D
- `mnist.pkl.gz` – Dataset file (required)

## 🚀 How to Run
Each notebook is self-contained. Just open and run in Jupyter. Use `epochs=2` for quick tests, `epochs=30` for final results.
