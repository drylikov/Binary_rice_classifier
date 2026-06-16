




































































































































































# 🌾 Rice Type Classification (Binary)

This project focuses on classifying rice grain images into two types using a Convolutional Neural Network (CNN). The dataset consists of image samples of rice grains, and the goal is to accurately distinguish between the two categories.

---

## 📌 Problem Statement

Classify rice grain images into two distinct types using deep learning techniques. This is a binary classification task using CNNs on image data.

---

## 🧠 Model Summary

- **Architecture**: Custom CNN
- **Framework**: TensorFlow / Keras
- **Optimizer**: Adam
- **Loss Function**: Binary Crossentropy
- **Metrics**: Accuracy

---

## 🧪 Experimentation & Tuning

Initially, the model was trained with:

- `learning_rate = 0.001`
- `batch_size = 8`

This configuration led to **overfitting**, as the model performed well on training data but poorly on validation data.

To counter this:

- **Learning rate was reduced** to `0.0005`
- **Batch size was increased** to `32`

These changes improved generalization and reduced overfitting significantly.

---

## 📁 Dataset

- Two classes of rice grain images.
- Images are preprocessed (resized, normalized).
- Dataset is split into training and validation sets.

---

## 📊 Results

- **Final Training Accuracy**: 100%
- **Final Validation Accuracy**: 90.62%
- **Epochs**: 20

The model showed strong performance after tuning the learning rate and batch size.

---
