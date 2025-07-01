# 🧮 MNIST Digit Classification

This project is a beginner-friendly implementation of a Convolutional Neural Network (CNN) to classify handwritten digits from the **MNIST** dataset. It serves as a foundational exercise to understand deep learning concepts such as image preprocessing, CNN architecture, model training, and evaluation.

---

## 📚 Dataset

The MNIST dataset consists of:
- 60,000 training images
- 10,000 test images  
Each image is a grayscale 28x28 pixel of handwritten digits (0 to 9).

---

## 🧠 Model Overview

The model is a simple CNN architecture built using **TensorFlow/Keras**, consisting of:

- Convolutional Layers
- MaxPooling Layers
- Flatten Layer
- Fully Connected (Dense) Layers
- Softmax Output for 10-class classification

---

## 🚀 Key Features

- Image normalization and reshaping
- One-hot encoding of labels
- Model training with accuracy and loss plots
- Evaluation on test data with confusion matrix
- Sample predictions visualization

---

## 🛠️ Tech Stack

- Python 3.x  
- TensorFlow / Keras  
- NumPy  
- Matplotlib / Seaborn  
- Jupyter Notebook

---

## 📁 Project Structure

```bash
MNIST-digit-classification/
│
├── mnist_cnn.ipynb             # Main notebook
├── README.md                   # This file
├── model.png                   # (optional) Model architecture image
├── results/                    # (optional) Sample predictions, confusion matrix
