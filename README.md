# 💳 Credit Card Transaction Anomaly Detection using Isolation Forest

An industry-level Unsupervised Machine Learning project that detects anomalous (potentially fraudulent) credit card transactions using the **Isolation Forest** algorithm.

---

## 📌 Project Overview

Credit card fraud is one of the biggest challenges faced by financial institutions. Since fraudulent transactions are rare and often unlabeled, **Isolation Forest**, an unsupervised anomaly detection algorithm, is an effective solution.

This project demonstrates an end-to-end machine learning pipeline including:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Isolation Forest model training
- Anomaly detection
- Model evaluation
- Data visualization
- Model saving & loading
- Predicting anomalies on new transactions

---

## 🎯 Objectives

- Detect unusual credit card transactions.
- Build a scalable anomaly detection system.
- Reduce financial fraud using machine learning.
- Demonstrate an industry-level ML workflow.

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 📂 Project Structure

```
├── Isolation_Forest_Credit_Card_Anomaly_Detection.ipynb
├── dataset/
│   └── creditcard.csv
├── models/
│   └── isolation_forest.pkl
├── images/
├── README.md
└── requirements.txt
```

---

## ⚙️ Machine Learning Workflow

1. Import libraries
2. Load dataset
3. Data cleaning
4. Exploratory Data Analysis
5. Feature Engineering
6. Train Isolation Forest model
7. Generate anomaly scores
8. Evaluate model performance
9. Visualize anomalies
10. Save trained model
11. Predict anomalies on new transactions

---

## 📊 Algorithm Used

### Isolation Forest

Isolation Forest is an unsupervised anomaly detection algorithm that works by randomly partitioning data points.

**Advantages**
- Fast on large datasets
- Works without labeled data
- Handles high-dimensional features
- Suitable for fraud detection

---

## 📈 Model Output

The model classifies transactions into:

| Prediction | Meaning |
|------------|---------|
| 1 | Normal Transaction |
| -1 | Anomalous / Fraudulent Transaction |

---

## 📊 Visualizations Included

- Distribution plots
- Correlation heatmap
- Transaction amount distribution
- Anomaly distribution
- Scatter plots
- Feature analysis

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Credit-Card-Anomaly-Detection.git
```

Move into the project

```bash
cd Credit-Card-Anomaly-Detection
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

## ▶️ How to Run

1. Open the notebook.
2. Execute cells sequentially.
3. Train the Isolation Forest model.
4. Detect anomalous transactions.
5. Save the trained model.

---

## 📦 Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
joblib
jupyter
```

---

## 💼 Business Applications

- Banking
- Credit Card Fraud Detection
- Financial Risk Analysis
- Insurance Fraud Detection
- Cybersecurity
- Intrusion Detection
- Network Security
- E-commerce Payment Monitoring

---

## 📚 Learning Outcomes

This project demonstrates:

- Unsupervised Machine Learning
- Anomaly Detection
- Isolation Forest
- Data Visualization
- Feature Engineering
- Model Persistence
- Real-world Fraud Detection Pipeline

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Adarsh Tiwari**

If you found this project helpful, consider giving it a ⭐ on GitHub!
