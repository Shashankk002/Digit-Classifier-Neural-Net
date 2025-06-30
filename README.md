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
- **Mini-batch gradient descent** (optional extension)
- **One-hot encoding**
- **Confusion matrix** & test accuracy visualization

---

## 📈 Results

- **Test Accuracy**: ~89.5% (trained on just 1000 examples)
- **Confusion Matrix**: Shows excellent performance on most digits
- **Loss Curve**: Clear downward trend over training epochs

---

## 🧪 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/Digit-Classifier-NN-From-Scratch.git
   cd Digit-Classifier-NN-From-Scratch
   ```

2. Open the notebook:
   ```bash
   jupyter notebook
   ```

3. Run the notebook step-by-step.

---

## 📚 Learning Goals

- Understand **how neural networks work** internally
- Practice **manual implementation** of training algorithms
- Build intuition about **classification**, **probability**, and **loss functions**

---

## ✅ What Makes This Project Unique?

Unlike typical ML projects, this one avoids high-level libraries. Every step — from initialization to prediction — is implemented manually using only NumPy. Perfect for interviews, learning, and demonstrating **core ML understanding**.

---

## 🛠️ Tools Used

- Python 3.x
- NumPy
- Matplotlib
- Scikit-learn (only for data loading and final confusion matrix)

---

## 🔍 Bonus

Try extending the model with:
- More layers (deep networks)
- Activation functions (Tanh, Leaky ReLU)
- Mini-batch SGD or Adam optimizer

---

📌 **Author:** [Your Name]  
📬 **Contact:** [your.email@example.com]