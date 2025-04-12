# 🧠 Schizophrenia Detection System using Vision Transformer & Machine Learning

A Computer-Aided Diagnosis (CAD) system designed to detect schizophrenia from fMRI scans using a hybrid approach of Machine Learning and Deep Learning. This project utilizes **Vision Transformers (ViT)**, **VGG19**, and traditional **ML feature extractors** (GLCM, LBP, HOG) to classify brain scans with high accuracy and real-time response capabilities.

---

## 📊 Dataset  
- **Source:** [NUSDAST - Northwestern University Schizophrenia Data and Software Tool](https://nustast.northwestern.edu)  
- **Data Type:** Functional MRI (fMRI) scans  
- **Classification:** Healthy vs Schizophrenia

---

## 🚀 Key Features  
- **Accuracy:** 95%  
- **Sensitivity:** 97%  
- **Specificity:** 94%  
- **Real-time Diagnosis:** 3–5 seconds per scan

---

## 🧠 Methodology  

### 🔍 Feature Extraction  
- **Machine Learning Features:**  
  - GLCM (Gray-Level Co-occurrence Matrix)  
  - LBP (Local Binary Patterns)  
  - HOG (Histogram of Oriented Gradients)  

- **Deep Learning Features:**  
  - VGG19 (Transfer Learning)  
  - Vision Transformer (ViT)

### 🔁 Feature Fusion  
- Combined ML + DL features using **Recursive Feature Elimination (RFE)**  
- Improved classification precision and model generalization

---

## 🖥 Web Application  
- **Framework:** Flask  
- **Functionality:** Upload fMRI scan → Automatic feature extraction → Predict diagnosis  
- **Response Time:** 3–5 seconds  

---

## 📄 IEEE Publication  
> **Title:** *Validation of Vision Transformer Over CNN-based Pre-trained Model for Schizophrenia Diagnosis*  
> **Event:** IEEE Mysore Subdivision Conference, 2024

---

## 📦 Tech Stack  
- Python  
- TensorFlow / Keras  
- Scikit-learn  
- OpenCV  
- Flask  
- NumPy, Pandas, Matplotlib  

---
