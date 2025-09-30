# Fraud Detection Using Machine Learning and Deep Learning

## 📌 Overview
This project investigates fraud detection on the **Credit Card Fraud Detection dataset (Kaggle)** using multiple approaches:
 Classical Machine Learning (Logistic Regression, Decision Trees, Random Forest, Gradient Boosting, AdaBoost, KNN, SVM, XGBoost)
 Deep Learning (Artificial Neural Network - ANN)
 Unsupervised Learning (Autoencoder for anomaly detection)

The goal is to compare classical vs. modern approaches and highlight how hybrid systems can improve fraud detection in real-world applications.

---

## 📊 Dataset
 Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
 Transactions: 284,807
 Fraud Cases: 492 (~0.17% imbalance)
 Features: 28 PCA-transformed features, Time, Amount
 Target: `Class` (0 = normal, 1 = fraud)

---

## ⚙️ Methodology
1. Data preprocessing (scaling, train-test split, SMOTE for imbalance handling)
2. Train/test multiple algorithms
3. Evaluate with Precision, Recall, F1-score, ROC AUC
4. Compare results of ML vs. DL vs. Autoencoder

---

## 📈 Results (Highlights)
| Model            | Precision | Recall | F1-score | ROC AUC |
|------------------|-----------|--------|----------|---------|
| Random Forest    | 0.94      | 0.90   | 0.92     | 0.98    |
| XGBoost          | 0.95      | 0.91   | 0.93     | 0.99    |
| ANN              | 0.93      | 0.89   | 0.91     | 0.98    |
| Autoencoder      | 0.79      | 0.72   | 0.75     | 0.91    |

 **XGBoost and Random Forest** delivered the best supervised performance.  
 **ANN** achieved competitive results.  
 **Autoencoder** provides an unsupervised approach for fraud anomaly detection.  

---

## 🚀 Deployment
 Models can be integrated into **Streamlit** or **Flask** web apps.  
 Supports batch CSV uploads for fraud scoring.  
 Extendable for real-time fraud detection systems.  

---

## 🔮 Future Work
 Graph Neural Networks for fraud ring detection  
 Real-time detection with online learning  
 Federated learning across financial institutions  
 Streamlit/Flask dashboard deployment  

---

## 📂 Files
 `Fraud_Detection_Research_Report.pdf` → Full academic-style report  
 `notebook.ipynb` → Colab-ready notebook with ML + DL models  
 `README.md` → Project documentation  

---

##  Author
Developed as a research-oriented project combining **academic value** and **market relevance** in fraud detection.
# Fraud-Detection-Using-Machine-Learning-and-Deep-Learning-Approaches
It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.
