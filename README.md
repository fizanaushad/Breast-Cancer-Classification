# 🧠 Breast Cancer Classification using CNN (CancerNet)

![Python](https://img.shields.io/badge/Python-3.9-blue.svg)
![Keras](https://img.shields.io/badge/Keras-TensorFlow-orange.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## 📖 Overview
Breast cancer is one of the most common and deadly diseases among women worldwide.  
This project implements a **Convolutional Neural Network (CNN)** model, inspired by **CancerNet**, to automatically classify **breast histopathology images** into:

- ✅ **No Cancer (IDC Negative)**  
- ❌ **Cancer (IDC Positive)**  

The model was trained and evaluated on the **Breast Histopathology Images Dataset** from Kaggle, achieving strong classification performance.

---

## 📂 Dataset
- **Source:** [Breast Histopathology Images – Kaggle](https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images)  
- **Description:**
  - 277,524 **50×50 RGB image patches** from breast cancer histopathology slides  
  - Two classes:
    - `0` → IDC Negative (No Cancer)  
    - `1` → IDC Positive (Cancer)  

---

## ⚙️ Workflow
-> Data Preprocessing

-> Train / Validation / Test split

-> Normalization and augmentation (rotation, zoom, flips)

-> Model Architecture (CancerNet)

-> Convolutional layers with ReLU activation

-> MaxPooling layers

-> Fully connected dense layers

-> Softmax output for binary classification

-> Training

Optimizer: Adagrad

-> Loss: binary_crossentropy

-> Trained for 20–40 epochs

Evaluation: 

-> Accuracy

-> Classification Report (Precision, Recall, F1-score)

-> Confusion Matrix

-> Prediction

-> Predicts on individual images or a batch of random images


# 📊 Results
| Metric    | Value |
| --------- | ----- |
| Accuracy  | ~85%  |
| Precision | ~83%  |
| Recall    | ~86%  |
| F1-score  | ~84%  |

Achieved > 80% accuracy on the validation set.

Clear separation between cancerous and non-cancerous tissue patches.
# Plots:
<img width="571" height="460" alt="download" src="https://github.com/user-attachments/assets/efbeb524-4fa0-4636-9132-b441730ee7a2" />


