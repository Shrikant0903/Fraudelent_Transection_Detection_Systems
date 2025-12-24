# 🚨 Fraudulent Transaction Detection System using LightGBM

A machine learning project to detect fraudulent financial transactions using **LightGBM**, designed to work effectively with **highly imbalanced datasets** common in banking and fintech systems.

---

## 📌 Project Overview

Fraud detection is a critical task in financial systems where fraudulent transactions are very rare but costly.  
This project builds an end-to-end **Fraud Detection System** using **Light Gradient Boosting Machine (LightGBM)** to classify transactions as fraudulent or legitimate.

---

## 🧠 Problem Statement

Given historical transaction data, predict whether a transaction is fraudulent.

- **Input:** Transaction-related features  
- **Output:**  
  - `0` → Legitimate Transaction  
  - `1` → Fraudulent Transaction  

---

## 🏗️ System Architecture

📥 **Transaction Data**  
Raw financial transaction data collected from banking or payment systems.

⬇️

🧹 **Data Preprocessing**  
Cleaning missing values, scaling numerical features, and handling imbalance.

⬇️

🧠 **Feature Engineering**  
Creating meaningful features to improve fraud detection performance.

⬇️

📊 **Train–Test Split**  
Stratified sampling to preserve fraud vs non-fraud distribution.

⬇️

⚡ **LightGBM Model Training**  
Training a gradient boosting model optimized for imbalanced data.

⬇️

📈 **Model Evaluation**  
Performance evaluation using:
- Precision  
- Recall  
- F1-Score  
- ROC–AUC  



---

## 🛠️ Technologies Used

- **Programming Language:** Python  
- **Machine Learning Algorithm:** LightGBM  
- **Libraries Used:**
  - pandas
  - numpy
  - scikit-learn
  - lightgbm
  - matplotlib
  - seaborn
  - imbalanced-learn
  - joblib

---

## ⚙️ Installation & Setup

```bash
git clone https://github.com/your-username/Fraudulent_Transaction_Detection_System.git
cd Fraudulent_Transaction_Detection_System
pip install -r requirements.txt
