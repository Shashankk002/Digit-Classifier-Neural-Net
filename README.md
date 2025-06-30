# 🧠 Digit Classifier from Scratch using Neural Networks

A beginner-friendly machine learning project that builds a **digit recognizer (0–9)** from the ground up using **only NumPy** — no machine learning libraries like Scikit-learn or TensorFlow. The entire pipeline is written from scratch to demonstrate mathematical understanding and implementation of neural networks.

---

## 📌 Project Overview

This project tackles the classic **MNIST digit classification** problem using a simple neural network with:
- One hidden layer (ReLU activation)
- One output layer (Softmax for multiclass classification)
- Manual gradient computation via **backpropagation**
- **Cross-entropy loss** and **batch gradient descent**

The model is trained on a subset of 1000 images and evaluated on the test set of 14,000+ samples.

---

## 🔢 Neural Network Architecture

```
Input Layer (784 nodes)
        ↓
Hidden Layer (128 ReLU neurons)
        ↓
Output Layer (10 Softmax nodes)
```

---

## 💡 Key Concepts Implemented

- **Forward pass** with ReLU and Softmax
- **Cross-entropy loss** computation
- **Backpropagation** with manual gradient computation
- **One-hot encoding**
- **Confusion matrix** & test accuracy visualization

---

## 📈 Results

- **Test Accuracy**: ~95.0% (trained on just 10000 examples)
- **Confusion Matrix**: Shows excellent performance on most digits
- **Loss Curve**: Clear downward trend over training epochs

---

## 📚 Learning Goals

- Understand **how neural networks work** internally
- Practice **manual implementation** of training algorithms
- Build intuition about **classification**, **probability**, and **loss functions**

---

## 🛠️ Tools Used

- Python
- NumPy
- Matplotlib
- Scikit-learn (only for data loading and final confusion matrix)

---