# Alpha Internship Task 3 — Handwritten Character Recognition

## 📌 Project Overview

This project implements a **Handwritten Character Recognition System** using a **Convolutional Neural Network (CNN)** and the **MNIST handwritten digit dataset**.

The model is trained to recognize handwritten digits from **0 to 9** using image processing and deep learning techniques.

This project was developed as part of **Alpha Internship — Task 3**.

---

## 🎯 Objective

The main objective of this project is to build a deep learning model capable of identifying handwritten digits from input images.

The project demonstrates:

* Image preprocessing
* Data normalization
* Convolutional Neural Networks
* Model training and validation
* Model evaluation
* Confusion matrix analysis
* Classification metrics
* Handwritten digit prediction

---

## 📊 Dataset

The **MNIST dataset** was used for this project.

| Property        | Details         |
| --------------- | --------------- |
| Dataset         | MNIST           |
| Training Images | 60,000          |
| Testing Images  | 10,000          |
| Image Size      | 28 × 28 pixels  |
| Image Type      | Grayscale       |
| Classes         | 10 (Digits 0–9) |

Each image represents a handwritten digit between **0 and 9**.

---

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Scikit-learn
* Seaborn
* Google Colab
* GitHub

---

## 🧠 Model Architecture

The CNN model consists of:

1. Convolutional Layer — 32 filters
2. Max Pooling Layer
3. Convolutional Layer — 64 filters
4. Max Pooling Layer
5. Flatten Layer
6. Dense Layer — 128 neurons
7. Output Layer — 10 neurons with Softmax activation

### Model Configuration

* **Optimizer:** Adam
* **Loss Function:** Sparse Categorical Crossentropy
* **Epochs:** 5
* **Batch Size:** 64
* **Validation Split:** 10%

---

## 🔄 Methodology

The project follows these steps:

```text
MNIST Dataset
      ↓
Data Loading
      ↓
Image Visualization
      ↓
Pixel Normalization
      ↓
Reshaping Images
      ↓
CNN Model Creation
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Confusion Matrix
      ↓
Classification Report
      ↓
Digit Prediction
```

---

## 📈 Model Evaluation

The trained CNN was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

The model achieved approximately **99% validation accuracy**, demonstrating strong performance on handwritten digit recognition.

> The
