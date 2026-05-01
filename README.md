# 🧠 MNIST Digit Classification using CNN

This project implements a **Convolutional Neural Network (CNN)** to classify handwritten digits (0–9) using the popular **MNIST dataset**. The model is built using TensorFlow/Keras and trained on grayscale images of handwritten digits.

---

## 📌 Project Overview

The goal of this project is to correctly recognize handwritten digits using deep learning techniques. A CNN is used due to its strong performance in image classification tasks.

---

## 📂 Dataset

- **Dataset:** MNIST (Modified National Institute of Standards and Technology)
- **Source:** Built-in dataset from Keras
- **Training samples:** 60,000 images
- **Test samples:** 10,000 images
- **Image size:** 28 × 28 pixels (grayscale)

---

## 🧠 Model Architecture

The CNN model consists of:

- Convolutional Layer (ReLU activation)
- Max Pooling Layer
- Convolutional Layer (ReLU activation)
- Max Pooling Layer
- Flatten Layer
- Fully Connected Dense Layer
- Output Layer (Softmax activation for 10 classes)

---

## ⚙️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Google Colab

---

## 🚀 Workflow

1. Load and preprocess MNIST dataset
2. Normalize pixel values (0–255 → 0–1)
3. Build CNN model
4. Train the model on training data
5. Evaluate performance on test data
6. Visualize predictions

---

## 📊 Results

- **Training Accuracy:** *(add your value here)*
- **Validation Accuracy:** *(add your value here)*
- **Test Accuracy:** *(add your value here)*

The model performs well on unseen handwritten digit images.

---

## 🔍 Sample Predictions

Add some example images with predicted labels here:

- Correct predictions
- Misclassified examples (optional but impressive)

---

## 📈 Visualization

Include:
- Accuracy vs Epoch graph
- Loss vs Epoch graph
- Confusion Matrix

---

## ▶️ How to Run

### In Google Colab:
1. Open the notebook
2. Run all cells sequentially
3. No additional setup required (dataset is built-in)

### Locally (optional):
```bash
pip install tensorflow numpy matplotlib
