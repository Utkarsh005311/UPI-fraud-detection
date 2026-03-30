# 💳 UPI Fraud Detection using Machine Learning

## 📌 Overview

This project aims to detect fraudulent UPI transactions using machine learning techniques. The dataset is highly imbalanced, making fraud detection challenging.

---

## 🚀 Key Features

* Data preprocessing and cleaning
* Feature engineering (transaction patterns)
* Handling class imbalance
* Model training using Random Forest
* Performance evaluation using precision & recall

---

## 🧠 Approach

* Removed data leakage features (`isFlaggedFraud`, IDs)
* Focused on **recall instead of accuracy**
* Used `class_weight="balanced"`
* Improved fraud detection by adjusting threshold (0.5 → 0.3)

---

## 📊 Results

* Accuracy: ~99%
* Precision (Fraud): ~0.55
* Recall (Fraud): improved significantly after tuning

---

## ⚠️ Note

The dataset is highly imbalanced, so accuracy alone is misleading.
Recall is prioritized to detect more fraudulent transactions.

---

## 📁 How to Run

1. Install dependencies
2. Run the notebook

---

## Author

Utkarsh Tiwari
