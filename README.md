# 🌿 Bell Pepper Disease Detection using Deep Learning

An AI-powered image classification system that detects diseases in bell pepper leaves using Deep Learning and Transfer Learning techniques. The model is trained on approximately **8,500 images** and helps identify plant diseases for smarter and more efficient agricultural practices.

---

## 📌 Project Overview

Early detection of plant diseases is essential for improving crop quality and reducing agricultural losses. This project uses Convolutional Neural Networks (CNNs) along with Transfer Learning models to classify bell pepper leaf images into healthy and diseased categories with high accuracy.

---

## 🚀 Features

- 🌱 Detects diseases in Bell Pepper leaves
- 🧠 Deep Learning-based image classification
- 📷 Trained on ~8,500 leaf images
- 🔄 Data preprocessing and augmentation
- ⚡ Transfer Learning using ResNet50 and MobileNetV2
- 📊 Achieved approximately **98% accuracy**
- 📈 Evaluated using Precision, Recall, F1-Score, and Accuracy

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- OpenCV
- Scikit-learn

---

## 📂 Dataset

- Approximately **8,500 Bell Pepper leaf images**
- Contains healthy and diseased leaf samples
- Images were preprocessed before training

### Preprocessing Steps

- Image Resizing
- Normalization
- Train-Test Split
- Data Augmentation

---

## 🔄 Data Augmentation

To improve model generalization and reduce overfitting, the following augmentation techniques were applied:

- Random Rotation
- Horizontal Flip
- Vertical Flip
- Zoom
- Width & Height Shift
- Brightness Adjustment
- Shearing

---

## 🧠 Deep Learning Models

### ResNet50
- Transfer Learning
- Fine-tuned on Bell Pepper dataset

### MobileNetV2
- Lightweight architecture
- Faster inference
- Suitable for real-time deployment

---

## 📊 Model Performance

| Metric | Score |
|---------|-------|
| Accuracy | ~98% |
| Precision | High |
| Recall | High |
| F1-Score | High |

The model demonstrated strong classification performance and generalized well on unseen test images.

