#  Credit Card Fraud Detection using Homomorphic & Order-Preserving Encryption

This project demonstrates a **privacy-preserving approach** to detecting credit card fraud using **Homomorphic Encryption (HE)** and **Order-Preserving Encryption (OPE)**. By leveraging **Paillier encryption** and **OPE**, the model can perform predictions on encrypted data—ensuring that sensitive transaction information remains secure throughout the entire inference process.

> ⚡ Built with `XGBoost`, `Random Forest`, `Paillier Encryption`, `OPE`

---

## 🚀 Features

-  **Fraud Detection on Encrypted Data**
-  **Paillier Homomorphic Encryption** for secure arithmetic operations
-  **Order-Preserving Encryption (OPE)** for encrypted comparisons (e.g., thresholds, conditions)
-  **XGBoost & Random Forest** models trained on an imbalanced fraud dataset
-  **Encrypted Predictions + Decryption via Private Key**


---

## 🧠 Project Overview

Traditional machine learning models expose input and output values during inference. In this project, predictions are made directly on **encrypted data**, enabling fraud detection **without decrypting sensitive user information**.

###  Workflow:
1. Preprocess dataset & handle class imbalance
2. Train XGBoost & Random Forest models on plaintext
3. Encrypt numerical features using **Paillier Encryption**
4. Encrypt comparison-sensitive features using **Order-Preserving Encryption**
5. Perform model inference directly on encrypted inputs
6. Decrypt predictions using private keys


---

## 🧰 Libraries Used

- `numpy`, `pandas`, `seaborn`
- `ope` (for Order-Preserving Encryption)
- `phe` (for Paillier Homomorphic Encryption)
- `xgboost`, `sklearn`


---

