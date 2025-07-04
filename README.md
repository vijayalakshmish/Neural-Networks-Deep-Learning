# Neural-Networks-Deep-Learning
# 🧠 CNN Projects – CIFAR-10 & Fashion MNIST

This repository contains two deep learning projects that apply Convolutional Neural Networks (CNNs) using TensorFlow/Keras to perform image classification on:
- CIFAR-10 (color images of everyday objects)
- Fashion MNIST (grayscale images of clothing items)

---

## 📁 Projects

### 🔹 Project 1: CIFAR-10 Classification
- **Dataset**: CIFAR-10
- **Classes**: ['airplane', 'automobile', 'bird', 'cat', 'deer', 'dog', 'frog', 'horse', 'ship', 'truck']
- **Model Summary**:
  - 3 Conv2D layers
  - MaxPooling after each Conv
  - Dense(64) + Dense(10)
- **Test Accuracy**: ~71%

### 🔹 Project 2: Fashion MNIST Classification
- **Dataset**: Fashion MNIST
- **Classes**: ['T-shirt/top', 'Trouser', 'Pullover', ..., 'Ankle boot']
- **Model Summary**:
  - 2 Conv2D + MaxPooling
  - Dense(128) + Dropout(0.5) + Softmax
- **Test Accuracy**: ~91%

---

## 🧪 How to Run

```bash
 Optionally in Colab:
Open the notebook in Google Colab

Or clone and run locally

cd Neural-Networks-Deep-Learning
pip install tensorflow matplotlib
jupyter notebook 12_02_2025_cnn_two_different_projects.ipynb
