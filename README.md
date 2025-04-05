
#  Credit Card Fraud Detection using Homomorphic Encryption

This project demonstrates a **privacy-preserving approach** to detecting credit card fraud using **Homomorphic Encryption (HE)**. By leveraging **Paillier encryption**, the model can perform predictions on encrypted data—ensuring that sensitive transaction information remains secure throughout the entire inference process.

> ⚡ Built with `XGBoost`, `Random Forest`, `Paillier Encryption`, and `Streamlit`.

---

## 🚀 Features

-  **Fraud Detection on Encrypted Data**
-  **Paillier Homomorphic Encryption** for secure predictions
-  **XGBoost & Random Forest** models trained on an imbalanced fraud dataset
-  **Encrypted Predictions + Decryption via Private Key**
-  **Streamlit App** for interactive demo
-  **CSV Input Support** for batch testing (including encrypted columns and keys)

---

## 🧠 Project Overview

Traditional machine learning models expose input and output values during inference. In this project, predictions are made directly on **encrypted data**, enabling fraud detection **without decrypting sensitive user information**.

### Workflow:
1. Preprocess dataset & handle class imbalance
2. Train XGBoost & Random Forest models on plaintext
3. Encrypt input features using **Paillier Encryption**
4. Perform model inference on encrypted inputs
5. Decrypt predictions using private keys
6. Visualize results using a **Streamlit dashboard**

---




Library Used:numpy,pandas,seaborn,ope

Frontend:Streamlit

 
