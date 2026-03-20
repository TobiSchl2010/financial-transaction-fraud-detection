# 💳 Financial Transaction Fraud Detection  

**Explainable Machine Learning for Large-Scale Imbalanced Data (5M+ Transactions)**  

[![Python](https://img.shields.io/badge/Python-3.11-blue)](https://www.python.org/)  
[![uv](https://img.shields.io/badge/uv-Modern_Python-black)](https://astral.sh/uv)  
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)  

---

## 🚀 Overview  

Fraud detection in financial systems is a **high-impact, real-world machine learning problem** characterized by extreme class imbalance and strict reliability requirements.  

This project develops an **interpretable and scalable ML pipeline** to detect fraudulent transactions in a dataset of over **5 million entries**, with **<1% fraud cases**.  

The focus lies on building a system that is not only accurate, but also:  
- **Explainable** → transparent model decisions  
- **Scalable** → efficient processing of large datasets  
- **Robust** → stable performance under class imbalance  

---

## 📂 Dataset  

This project uses the **"Financial Transactions Dataset for Fraud Detection"** from Kaggle.  

It is a **large-scale synthetic dataset** designed to closely mimic real-world financial behavior and fraud patterns.  

### Key Characteristics  

- **5 million transactions**  
- Highly **imbalanced (<1% fraud cases)**  
- Realistic **behavioral and anomaly patterns**  

### Included Features  

- **Transaction Details**  
  - transaction ID, timestamp  
  - sender & receiver accounts  
  - amount and transaction type  

- **Behavioral Features**  
  - time since last transaction  
  - spending deviation score  
  - velocity score  
  - geo-anomaly score  

- **Metadata**  
  - location  
  - device information  
  - payment channel  
  - IP address / device hash  

- **Fraud Labels**  
  - binary classification (`is_fraud`)  
  - fraud type (e.g. money laundering, account takeover)  

---

### Use Cases  

The dataset is suitable for:  
- binary and multiclass classification  
- fraud detection systems  
- time-series anomaly detection  
- feature engineering and explainable ML  

---


## 🎯 Problem Statement  

In real-world applications, fraud detection systems must balance two competing risks:  

- **False Negatives** → direct financial loss  
- **False Positives** → customer dissatisfaction and trust erosion  

> The key challenge:  
> Detect rare fraudulent transactions **accurately, efficiently, and transparently at scale**.

---

## 🧠 Key Features  

- End-to-end **machine learning pipeline**  
- Handling of **extreme class imbalance (<1%)**  
- Advanced techniques:  
  - resampling (SMOTE, undersampling)  
  - class weighting  
  - anomaly detection approaches  
- **Model interpretability** using SHAP / feature importance  
- Designed for **real-world scalability**  

---

## ⚙️ Tech Stack  

- **Python 3.11**  
- **uv** (fast dependency management)  
- **pandas / NumPy**  
- **scikit-learn / XGBoost / LightGBM**  
- **SHAP** (model explainability)  

---

