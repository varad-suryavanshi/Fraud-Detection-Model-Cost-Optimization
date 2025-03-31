# Credit Card Fraud Detection Model

This project implements a machine learning model to detect fraudulent credit card transactions. It uses a dataset of transaction records to build a predictive model that distinguishes between legitimate and fraudulent behavior, with an emphasis on cost optimization.

## 📌 Objective

Credit card fraud leads to significant financial losses. This notebook explores how machine learning can be used to detect fraud more effectively and reduce false positives, which can be costly for both banks and customers.

## 🧠 Model Overview

- Exploratory Data Analysis (EDA) on transaction features
- Data preprocessing (handling imbalance, feature scaling)
- Model training using [insert model used, e.g. Logistic Regression / Random Forest / XGBoost]
- Evaluation using metrics like:
  - Confusion Matrix
  - ROC-AUC Score
  - Precision / Recall / F1-Score
- Cost-based threshold optimization to balance fraud detection vs false alarms

## 📊 Dataset

- Dataset: `cc_transactions.csv` (not included due to size)
- Size: ~618MB
- Contains anonymized transaction data with labels indicating fraud or legitimate behavior

## 🧰 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`, `seaborn` for visualization
- `scikit-learn` for ML modeling and evaluation

## 💡 Features

- Handles imbalanced data (class imbalance between fraud and legit)
- Visualizes key insights from the data
- Threshold tuning based on cost-benefit analysis
- Reproducible notebook format (`.ipynb`)

## 🚀 How to Run

1. Clone the repository
2. Place the dataset file `cc_transactions.csv` in the same directory
3. Open the notebook:

```bash
jupyter notebook Credit-Card-Fraud-Detection-Model.ipynb
