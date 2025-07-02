# Digit Classifier from Scratch using Neural Networks

A hands-on machine learning project where I built a digit recognizer (0–9) using only NumPy — without relying on libraries like Scikit-learn or TensorFlow. The entire model pipeline, including training logic, was written manually to understand the math and working of neural networks at a deeper level.

---

## Project Overview

This project solves the classic **MNIST digit classification** problem using a simple neural network with:
- One hidden layer (ReLU activation)
- One output layer (Softmax for multiclass classification)
- Manual gradient computation via **backpropagation**
- **Cross-entropy loss** and **batch gradient descent**

The model is trained on a subset of 1000 images and evaluated on the test set of 14,000+ samples.

---

## Neural Network Architecture

```
Input Layer (784 nodes)
        ↓
Hidden Layer (128 ReLU neurons)
        ↓
Output Layer (10 Softmax nodes)
```

---

## Key Concepts Implemented

- **Forward pass** with ReLU and Softmax
- **Cross-entropy loss** computation
- **Backpropagation** with manual gradient computation
- **One-hot encoding**
- **Confusion matrix** & test accuracy visualization

---

## Results

- **Test Accuracy**: ~95.0% (trained on just 10000 examples)
- **Confusion Matrix**: Shows excellent performance on most digits
- **Loss Curve**: Clear downward trend over training epochs

---

## Tools Used

- Python
- NumPy
- Matplotlib
- Scikit-learn (only for data loading and final confusion matrix)

---
