# CreditCard-Fraud-Analysis

📄 Project Overview

This project analyzes a credit card fraud dataset containing transactions made by European cardholders in September 2013. With only 0.172% of the transactions labeled as fraudulent, the dataset is highly imbalanced. The analysis involves techniques like clustering, PCA, and time-series exploration to uncover patterns and improve fraud detection.

🔑 Key Features

Dataset Summary:
Total Transactions: 284,807
Fraudulent Transactions: 492 (0.172%)
Features: PCA-transformed numerical features, transaction Time, and Amount.
Techniques Applied:
EDA: Visualize transaction amounts, time patterns, and class imbalance.
Clustering: Identify groups of transactions to isolate potential fraud.
PCA Analysis: Leverage anonymized features for dimensionality reduction and fraud prediction.
Time-Series Analysis: Explore temporal trends in fraudulent transactions.

📊 Key Insights

Fraudulent transactions are typically:
Small in amount (often below €200).
Occurring at unusual hours, such as late at night or early morning.
Clustering revealed certain high-risk clusters with a higher prevalence of fraud.
PCA-transformed features effectively encode patterns for fraud detection.

🚀 Tools & Technologies

Programming Language: Python

Libraries:

- Data Manipulation: Pandas, NumPy

- Visualization: Matplotlib, Seaborn

- Clustering: scikit-learn

- Dimensionality Reduction: PCA

Dataset:

- https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

