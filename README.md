# 🧠 MNIST Digit Classification with CNN

This project demonstrates how to use Convolutional Neural Networks (CNNs) with TensorFlow and Keras to classify handwritten digits from the MNIST dataset with high accuracy.

---

---

## 🔍 Overview

The MNIST dataset is a benchmark in machine learning, containing 70,000 images of handwritten digits (0–9). This CNN model is trained to recognize these digits from grayscale 28x28 images.

---

## 🧠 Model Architecture
Input: (28, 28, 1)

→ Conv2D: 32 filters (3x3), ReLU
→ MaxPooling2D: pool size (2x2)
→ Conv2D: 64 filters (3x3), ReLU
→ MaxPooling2D: pool size (2x2)
→ Flatten
→ Dropout (rate=0.5)
→ Dense: 128 units, ReLU
→ Dense: 10 units, Softmax

---
##Test Accuracy: ~98%


