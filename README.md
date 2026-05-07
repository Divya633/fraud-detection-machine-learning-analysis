# Credit Card Fraud Detection Model Comparison

## Overview

This project implements and compares multiple machine learning models for detecting fraudulent credit card transactions using classification and anomaly detection techniques.

The system evaluates model performance using precision, recall, F1-score, ROC-AUC, and confusion matrix analysis to identify the most effective fraud detection approach.

---

## Features

- Fraud transaction classification
- Multiple model comparison
- Imbalanced dataset handling
- Data preprocessing and scaling
- Performance evaluation metrics
- Confusion matrix visualization
- ROC-AUC analysis
- Feature importance analysis

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- XGBoost

---

## Models Compared

- Logistic Regression
- Random Forest
- Decision Tree
- XGBoost
- Isolation Forest
- Support Vector Machine (SVM)

---

## Dataset

The project uses a credit card transaction dataset containing legitimate and fraudulent transactions.

Dataset includes:
- transaction amount
- anonymized features
- fraud labels
- transaction patterns

---

## Methodologies Used

- Classification Modeling
- Anomaly Detection
- Data Normalization
- SMOTE / Imbalanced Data Handling
- Cross Validation
- Feature Scaling

---

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

---

## Project Structure

credit-card-fraud-detection-comparison/
│
├── data/
├── models/
├── notebooks/
├── screenshots/
├── src/
├── app.py
├── requirements.txt
├── README.md
└── .gitignore

---

## Run Locally

Install dependencies:

pip install -r requirements.txt

Run the project:

python app.py

---

## Future Improvements

- Real-time fraud detection
- Deep learning integration
- Streaming transaction analysis
- Explainable AI (XAI)
- Deployment using Streamlit
