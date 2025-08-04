# 🧠 MNIST Handwritten Digit Recognition using CNN (PyTorch)

This project implements a Convolutional Neural Network (CNN) to recognize handwritten digits from the MNIST dataset using **PyTorch**. It is trained, evaluated, and tested directly in **Google Colab**.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO_NAME/blob/main/MNIST_CNN.ipynb)

---

## 📌 Project Features

- 🧩 Dataset: MNIST (60,000 training + 10,000 testing images)
- 🧠 Model: Convolutional Neural Network (CNN)
- 📉 Evaluation: Accuracy, Loss
- 🖼️ Custom digit prediction (from user-uploaded images)
- 💾 Model saving and reloading with `torch.save` and `torch.load`

---

## 🛠️ Tech Stack

- Python 3
- PyTorch
- torchvision
- Google Colab
- matplotlib
- PIL (for custom image input)

---

## 🚀 How to Use

### 🔗 Open in Colab

Click the badge above ☝️ to run it directly in Colab.

### 🧪 Steps Performed

1. Load and visualize the MNIST dataset
2. Define a CNN model
3. Train the model (5 epochs)
4. Evaluate on test data
5. Save and load the model
6. Test on your own handwritten digit image

---

## 🎯 Results

| Epoch | Train Accuracy | Test Accuracy |
|-------|----------------|---------------|
| 1     | 94.67%         | 97.32%        |
| 2     | 97.81%         | 98.15%        |
| 3     | 98.05%         | 98.16%        |
| 4     | 98.21%         | 98.11%        |
| 5     | 98.28%         | 98.20%        |

---

## 📂 Custom Image Prediction

You can upload your own handwritten digit (28x28 grayscale image), and the model will predict the digit.

---
