# 🖐️ American Sign Language (ASL) Recognition

> A Computer Vision project for recognizing **American Sign Language (ASL)** hand gestures using image preprocessing, PCA-based feature extraction, and Transfer Learning with MobileNetV2.

![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange)
![OpenCV](https://img.shields.io/badge/OpenCV-ComputerVision-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-red)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📌 Overview

This project recognizes **29 American Sign Language (ASL)** hand gestures (A–Z + Space, Delete, Nothing) using a complete Computer Vision pipeline. The system combines image preprocessing, PCA feature extraction, and a MobileNetV2 classifier to achieve high recognition accuracy.

---

## 🚀 Features

- ASL hand gesture recognition
- Image preprocessing pipeline
- Skin segmentation
- Edge detection using Canny
- Data augmentation
- PCA for dimensionality reduction
- Transfer Learning with MobileNetV2
- Interactive GUI for image prediction
- Model and preprocessing artifacts saving
- Ready for real-time inference

---

## 📂 Dataset

- **Dataset:** ASL Alphabet Dataset
- **Classes:** 29
- **Images:** ~87,000
- **Image Size:** 200 × 200 pixels

---

## ⚙️ Project Pipeline

```text
Dataset
   │
   ▼
Image Preprocessing
   │
   ▼
Skin Segmentation
   │
   ▼
Edge Detection
   │
   ▼
Data Augmentation
   │
   ▼
PCA Feature Extraction
   │
   ▼
MobileNetV2 Classification
   │
   ▼
Prediction & GUI
```

---

## 🛠️ Technologies

- Python
- TensorFlow / Keras
- OpenCV
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- PCA
- MobileNetV2

---

## 📈 Results

- **29 ASL Classes**
- **Validation Accuracy:** **94.13%**
- PCA retained **95%** of the data variance while reducing dimensionality.
- Interactive GUI for classifying uploaded hand gesture images.

---


## 🔮 Future Improvements

- Real-time webcam recognition
- MediaPipe hand tracking
- Transformer-based vision models
- Deployment as a web application

---


GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/yourprofile
