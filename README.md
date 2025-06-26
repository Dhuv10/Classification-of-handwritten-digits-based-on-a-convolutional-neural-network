# Classification-of-handwritten-digits-based-on-a-convolutional-neural-network
Handwritten digit classification using a CNN trained on the MNIST dataset with 99.2% accuracy.
# 🔢 Handwritten Digit Classification using CNN (MNIST)

This project implements a Convolutional Neural Network (CNN) for classifying handwritten digits from the **MNIST** dataset. The model achieves over **99.2% accuracy** and is optimized for high precision and low false positive rates.

---

## 📌 Overview

- Dataset: **MNIST** (70,000 grayscale digit images: 28x28 pixels)
- Model: Deep CNN with Conv2D, MaxPooling, Dense, and Dropout layers
- Achievements:
  - **Accuracy**: 99.23%
  - **Precision**: 99.25%
  - **Recall**: 99.22%
  - **F1-Score**: 99.23%
- Optimizer: Adam
- Loss: Categorical Cross-Entropy

---

## 🧰 Technologies Used

- Python
- TensorFlow / Keras
- NumPy, matplotlib
- scikit-learn (for metrics)

---

## 🧠 Model Architecture

- Conv2D → ReLU → MaxPooling
- Conv2D → ReLU → MaxPooling
- Flatten → Dense → Dropout → Dense (Output with softmax)

---

## 📂 Folder Structure

| Folder        | Description                             |
|---------------|-----------------------------------------|
| `src/`        | Scripts to train and evaluate the model |
| `notebooks/`  | Jupyter notebook for EDA + training     |
| `model/`      | Saved Keras model in .h5 format         |
| `results/`    | Visual outputs like accuracy curves     |
