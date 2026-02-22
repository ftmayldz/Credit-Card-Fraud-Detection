Credit Card Fraud Detection
Problem

Detect fraudulent credit card transactions using machine learning on a highly imbalanced dataset.

Dataset

Source: Kaggle

Target variable: Class

0 → Normal

1 → Fraud

Fraud transactions represent less than 1% of the data.

Approach

Data exploration

Train-test split

Logistic Regression model

Handled imbalance using class_weight='balanced'

Evaluated with:

Confusion Matrix

Precision & Recall

ROC-AUC Score

Results

ROC-AUC: 0.97

Precision: 0.04

Recall: 0.89

The model detects most fraud cases (high recall) but produces many false positives (low precision), which is a common trade-off in fraud detection systems
