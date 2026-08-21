Credit Card Anomaly Detection using Isolation Forest
🚀 Project Overview

This project implements an Unsupervised Machine Learning solution for detecting suspicious and unusual credit-card transactions using the Isolation Forest algorithm.

The main objective is to identify transactions that behave differently from normal transactions based on factors such as transaction amount, transaction time, distance from home, merchant risk, transaction frequency, device changes, failed attempts, and international activity.

Machine Learning Type: Unsupervised Learning
Algorithm: Isolation Forest
Domain: Banking & Financial Fraud Detection
Project Level: Industry-Oriented

🎯 Business Problem

Credit-card fraud is difficult to detect because fraudulent transactions are usually a very small percentage of all transactions.

Traditional supervised machine-learning models require a large amount of accurately labeled fraud data. In many real-world situations, such labels are limited or unavailable.

Isolation Forest provides an effective solution by identifying observations that are significantly different from the majority of transactions.

Business Goal

Detect potentially suspicious transactions early so that they can be reviewed, blocked, or subjected to additional authentication.

💡 Solution

The project uses Isolation Forest, an anomaly-detection algorithm that isolates unusual observations.

The model analyzes transaction behavior and generates:

🟢 Normal Transaction
🔴 Anomalous / High-Risk Transaction
📊 Anomaly Score

A higher anomaly score indicates that the transaction is more unusual compared with normal transaction behavior.

🧠 Why Isolation Forest?

Isolation Forest is particularly useful for anomaly detection because:

It does not require fraud labels for training.
It works well with high-dimensional datasets.
It is computationally efficient.
It can detect unusual patterns automatically.
It is suitable for large-scale anomaly detection.
It can identify rare observations without manually defining every fraud rule.
📊 Dataset

The project uses a realistic synthetic credit-card transaction dataset.

Dataset Size
10,000 transactions
9,500 normal transactions
500 anomalous transactions
Features
Feature	Description
transaction_id	Unique transaction identifier
transaction_amount	Amount of the transaction
transaction_hour	Hour when transaction occurred
distance_from_home_km	Distance between transaction location and customer's home
merchant_risk_score	Risk score of merchant
transactions_last_24h	Number of transactions in previous 24 hours
device_change_count	Number of recent device changes
account_age_days	Age of customer account
failed_attempts	Number of failed transaction attempts
international_transaction	Whether transaction was international
transaction_datetime	Transaction date and time
actual_anomaly	Synthetic ground-truth label for evaluation
🔄 Project Workflow
Raw Transaction Data
        ↓
Data Loading
        ↓
Data Quality Checks
        ↓
Exploratory Data Analysis
        ↓
Feature Engineering
        ↓
Feature Scaling
        ↓
Isolation Forest
        ↓
Anomaly Prediction
        ↓
Anomaly Score
        ↓
Visualization
        ↓
Model Evaluation
        ↓
Business Recommendations
🛠️ Technologies Used
Programming Language
Python
Libraries
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Joblib
Machine Learning
Isolation Forest
StandardScaler
Classification Report
Confusion Matrix
ROC-AUC
📈 Exploratory Data Analysis

The project performs several EDA activities including:

1. Transaction Amount Distribution

Analyzes the distribution of transaction amounts and identifies unusual values.

2. Transaction Amount Box Plot

Helps identify extreme transaction amounts.

3. Transactions by Hour

Analyzes transaction activity throughout the day.

4. Correlation Heatmap

Shows relationships between numerical transaction features.
