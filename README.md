# TabNet-SQLi-Detection
Master's thesis - SQL Injection Detection using TabNet
# SQL Injection Detection using TabNet

This repository contains the source code and resources for the master's thesis titled:

**"Machine Learning-Based Approaches for SQL Injection Detection and Prevention Enhancement"**  
by **Abdalla Ghanem Ahmed**,  
Faculty of Graduate Studies for Statistical Research, Cairo University, 2025.

---

## 🧠 Project Overview

This project applies **TabNet**, a deep learning model optimized for tabular data, to detect SQL injection (SQLi) attacks in web applications using a supervised machine learning approach.

The goal is to provide:
- Better accuracy than traditional models.
- Faster detection.
- Explainability and robustness against adversarial SQLi.

---

## 📊 Dataset

- The dataset used is composed of labeled SQL queries (`benign` or `injection`).
- Preprocessed using **TF-IDF** vectorization with `1000` features.
- Input: Raw SQL query (text).
- Output: Label (0 = Normal, 1 = SQL Injection).

---

## ⚙️ Model Details

- Model: `TabNetClassifier` (from pytorch-tabnet).
- Preprocessing: TF-IDF Vectorizer (`sklearn`).
- Loss Function: Cross-entropy.
- Metrics: Accuracy, Precision, Recall, F1 Score, ROC AUC.
- Regularization: Early stopping, learning rate scheduler.

---

## 📈 Evaluation

- Confusion Matrix
- ROC Curve
- Accuracy, Precision, Recall, F1 Score
- In-notebook test interface for manual queries
- Gradio interface for user input detection (GUI)

---

## 📂 Project Structure
📁 TabNet-SQLi-Detection/
│
├── TabNet_SQLi_Detection.ipynb # Main notebook for training and evaluation
├── Modified_SQL_Dataset.csv # Dataset (if public or example provided)
├── requirements.txt # Python dependencies
├── README.md # Project documentation



