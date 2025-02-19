# Credit-Card-Fraud-Detection-Using-Python-And-ML
Credit Card Fraud Detection Using Python and Machine Learning

# Credit Card Fraud Detection - Project Overview
Fraudulent transactions are a major concern in the financial industry, costing billions of dollars annually. This project focuses on Credit Card Fraud Detection using Machine Learning, leveraging real-world transaction data to distinguish between legitimate and fraudulent activities. The primary objective is to accurately identify fraudulent transactions while minimizing false positives, ensuring that genuine transactions are not wrongly flagged.

# Project Approach
The dataset, obtained from Kaggle, contains 284,807 transactions, with only 0.17% labeled as fraud, making it highly imbalanced. To handle this, we applied data preprocessing techniques, including feature scaling, Principal Component Analysis (PCA), and class balancing methods like SMOTE (Synthetic Minority Oversampling Technique).
For fraud detection, we implemented and compared multiple models:
Logistic Regression – A simple yet effective classification model for binary fraud detection.
Isolation Forest – An anomaly detection algorithm that isolates fraudulent transactions.
Local Outlier Factor (LOF) – A density-based method to identify fraud as an outlier.

Each model was evaluated using key metrics such as precision, recall, accuracy, and confusion matrix analysis. The best-performing model was further optimized to enhance its predictive capabilities.

# Key Features of the Project
Exploratory Data Analysis (EDA): Visualizing transaction patterns, fraud distribution, and correlations.
Feature Engineering: Applying PCA transformation to anonymized variables for better model performance.
Model Evaluation: Using precision-recall tradeoff to select the best classifier.
Deployment Ready: The project includes a Flask-based web application to allow users to input transaction details and receive fraud predictions in real-time.

# Future Scope
While the current model achieves a high detection rate, further improvements can be made by integrating ensemble learning methods and deep learning techniques for more accurate fraud identification. Additionally, real-time fraud detection can be enhanced by integrating streaming data processing techniques.

This project demonstrates how machine learning can be effectively used to combat financial fraud, ensuring a more secure digital transaction ecosystem.

