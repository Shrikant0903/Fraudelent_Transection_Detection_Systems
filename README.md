# 🚨 Fraudulent Transaction Detection System  
### ⚡ Powered by LightGBM & Machine Learning

<p align="center">
  <img src="https://img.shields.io/badge/Machine%20Learning-LightGBM-brightgreen"/>
  <img src="https://img.shields.io/badge/Python-3.x-blue"/>
  <img src="https://img.shields.io/badge/Status-Completed-success"/>
  <img src="https://img.shields.io/badge/License-MIT-yellow"/>
</p>

---

## 📌 Project Overview

💳 Fraudulent transactions are rare but extremely costly.  
This project builds an **end-to-end Fraud Detection System** using **LightGBM**, optimized for **highly imbalanced financial datasets**.

✨ **Highlights**
- 🚀 Fast & scalable LightGBM model  
- ⚖️ Handles class imbalance effectively  
- 📊 Focus on Recall, F1-score & ROC-AUC  
- 🏦 Real-world banking use case  

---

## 🧠 Problem Statement

Given historical transaction data, predict whether a transaction is fraudulent.

🔹 **Input:** Transaction features  
🔹 **Output:**  
- `0` → ✅ Legitimate Transaction  
- `1` → 🚨 Fraudulent Transaction  

---

## 🏗️ System Architecture

📥 **Transaction Data**  
Raw financial transactions collected from payment systems.

⬇️  

🧹 **Data Preprocessing**  
- Missing value handling  
- Feature scaling  
- Class imbalance handling  

⬇️  

🧠 **Feature Engineering**  
- Transaction-based patterns  
- Amount & time-based features  

⬇️  

📊 **Train–Test Split**  
Stratified sampling to maintain fraud ratio.

⬇️  

⚡ **LightGBM Model Training**  
Gradient Boosting model optimized for tabular data.

⬇️  

📈 **Model Evaluation**  
Evaluated using:
- 🎯 Precision  
- 🔁 Recall  
- 🧮 F1-Score  
- 📉 ROC–AUC  

---


---

## 🛠️ Tech Stack & Tools

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/LightGBM-00A000"/>
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white"/>
</p>

---

## ⚙️ Installation

```bash
git clone https://github.com/your-username/Fraudulent_Transaction_Detection_System.git
cd Fraudulent_Transaction_Detection_System
pip install -r requirements.txt


