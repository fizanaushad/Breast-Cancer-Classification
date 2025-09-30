# Breast-Cancer-Classification
CNN model for Breast Cancer Histopathology Image Classification.
📖 Overview

This project implements a Convolutional Neural Network (CNN) to classify breast histopathology images as either:

Cancer (IDC Positive)

No Cancer (IDC Negative)

The model is inspired by CancerNet, a lightweight CNN designed for medical image analysis.
It was trained on the Breast Histopathology Images Dataset from Kaggle and achieves good performance on unseen test samples.

📂 Dataset

Source: Breast Histopathology Images (Kaggle)

Description:

277,524 50×50 RGB patches from breast cancer histopathology slides.

Two classes:

0 → IDC Negative (No Cancer)

1 → IDC Positive (Cancer)

⚙️ Project Workflow

Data Preprocessing

Train / Validation / Test split

Normalization and augmentation (rotation, zoom, flips)

Model Architecture (CancerNet)

Convolutional layers with ReLU activation

MaxPooling layers

Fully connected dense layers

Softmax output for binary classification

Training

Optimizer: Adagrad

Loss: binary_crossentropy

Trained for 20–40 epochs

Evaluation

Accuracy

Classification Report (Precision, Recall, F1-score)

Confusion Matrix

Prediction

Predicts on individual images

Can classify multiple random test images in batch
