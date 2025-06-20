# Math 371: Large-Scale Data Algorithms – Machine Learning Projects

This repository contains a series of machine learning projects completed for **Math 371: Large-Scale Data Algorithms**. The course emphasizes scalable, performance-efficient neural network models, activation function experimentation, cost function customization, and deep CNN architecture tuning using real-world datasets.

Each project reflects progressive skill-building in designing algorithms that scale, perform efficiently, and provide analytical insights.

## 📁 Projects Overview

### 🔹 [Project 1: Neural Network Fundamentals (MNIST)](./project1/)
- Baseline model execution and setup
- Classification performance tuning via learning rate
- Per-class accuracy analysis
- Training efficiency via stochastic data sampling

### 🔹 [Project 2: Cost & Regularization (MNIST)](./project2/)
- Custom softmax + log-likelihood implementation
- L1 regularization vs L2 comparison
- Activation function tuning with tanh

### 🔹 [Project 3: Deep CNNs (CIFAR-10)](./project3/)
- Use of ReLU and confusion matrix for class-wise analysis
- Custom convolutional architecture with four layers
- Efficient design using `AvgPool2d` to prevent extreme values

## 🧰 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

## 📦 Dataset Info

- **MNIST** dataset used in Projects 1 & 2 (`mnist.pkl.gz`)
- **CIFAR-10** used in Project 3 via `torchvision.datasets.CIFAR10`

## 🧠 Skills Demonstrated

- Algorithm design for scalability
- Efficient training and evaluation under resource constraints
- Cost and activation function customization
- Deep CNN design and performance tuning
- Runtime analysis and visualization

## 📜 License

This project is for educational use only.

