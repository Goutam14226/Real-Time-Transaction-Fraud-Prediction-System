# 🛡️ Real-Time Transaction Fraud Prediction System

<p align="center">

<img src="./assets/fraud-detection-banner.png" alt="Fraud Detection" width="900">

</p>

<h2 align="center">💳 Machine Learning Based Transaction Fraud Detection</h2>

<p align="center">
  <b>Detect suspicious financial transactions using Machine Learning, Risk Analytics and Statistical Techniques.</b>
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange?style=for-the-badge)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-red?style=for-the-badge&logo=scikit-learn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-purple?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?style=for-the-badge&logo=numpy)

</p>

---

## 🌟 Project Overview

Financial fraud is one of the major challenges faced by banks, fintech companies and digital payment platforms.

Every day, millions of transactions are generated. Among these transactions, only a very small percentage may be fraudulent.

The goal of this project is to build a **Machine Learning based fraud detection system** that can:

- 🔍 Analyze transaction behavior
- 🧮 Engineer meaningful risk features
- 📊 Identify suspicious transaction patterns
- 🤖 Train multiple Machine Learning models
- 📈 Evaluate model performance
- ⚖️ Compare different classification algorithms
- 📉 Measure discriminatory power using AUC, Gini and KS
- 🧪 Evaluate model calibration
- 📊 Monitor population stability using PSI

> 💡 **Main objective:** Build and evaluate a Machine Learning model capable of distinguishing fraudulent transactions from legitimate transactions.

---

# 🖼️ 1. Real-World Problem

<p align="center">
<img src="./assets/real-world-digital-payment.png" alt="Digital Payment Fraud" width="800">
</p>

Imagine a customer making a digital payment:

```text
Customer
   │
   ▼
💳 Transaction
   │
   ├── Amount
   ├── Time
   ├── Provider
   ├── Product
   ├── Payment Channel
   ├── Customer History
   └── Transaction Frequency
   │
   ▼
🤖 Fraud Detection Model
   │
   ├───────────────┐
   ▼               ▼
🟢 Genuine       🔴 Fraud
Transaction      Transaction
