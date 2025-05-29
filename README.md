# Sign Language Digit Recognition using CNNs

This project implements a Convolutional Neural Network (CNN) to recognize hand gestures representing digits (0–5) in American Sign Language (ASL).

---

## 🤟 Objective

To classify images of ASL hand signs into digit classes (0 through 5) using deep learning.

---

## 📊 Dataset

- The dataset contains labeled images for each digit from 0 to 5.
- Hand gesture images are typically grayscale or RGB.
- Preprocessing includes:
  - Resizing to a fixed input size (e.g., 64x64)
  - Normalization
  - One-hot encoding of labels

---

## 🏗️ Model Architecture

- **Input:** 64x64 grayscale or RGB images
- **Convolutional Layers:** Extract spatial features using `Conv2D + ReLU`
- **Pooling Layers:** Downsample using `MaxPooling2D`
- **Flattening:** Convert 2D features into 1D
- **Dense Layers:** Fully connected layers with dropout for regularization
- **Output:** Softmax layer for 6-class classification (digits 0–5)

---

## 🧪 Evaluation

- Accuracy and loss visualizations for training and validation
- Confusion matrix to evaluate predictions
- Model shows high accuracy on both training and test sets

---

## 📊 Results

- Test Accuracy: ~90–95%
- Strong generalization on unseen data
- Sample predictions visualized and analyzed

---

## 🛠️ Technologies Used

- Python 3.x
- TensorFlow / Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/RishitSaxena55/sign-language-digit-cnn.git
   cd sign-language-digit-cnn
