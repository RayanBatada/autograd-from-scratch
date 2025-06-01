# Autograd from Scratch

This project implements a simple reverse-mode automatic differentiation (autograd) engine from scratch in Python. It’s inspired by Andrej Karpathy’s [micrograd](https://github.com/karpathy/micrograd), and is designed to help understand the inner workings of neural networks, backpropagation, and gradient-based optimization — all without using external machine learning libraries.

## 🚀 Features

- Scalar `Value` class with automatic gradient tracking
- Operator overloading for math operations (`+`, `-`, `*`, `**`, etc.)
- Backpropagation via `.backward()` method
- Intuitive and readable implementation using object-oriented Python
- (Optional) Neural network example using the custom autograd engine

## 📂 Files

- `Autograd.ipynb`: A step-by-step Jupyter Notebook explaining and implementing the autograd engine.

## 🧠 Concepts Covered

- Reverse-mode automatic differentiation
- Computational graphs
- Chain rule & gradient propagation
- Object-oriented programming
- Basics of neural networks

## ▶️ Running the Notebook

1. Clone the repo:
    ```bash
    git clone https://github.com/RayanBatada/autograd-from-scratch.git
    cd autograd-from-scratch
    ```

2. Launch Jupyter:
    ```bash
    jupyter notebook Autograd.ipynb
    ```
