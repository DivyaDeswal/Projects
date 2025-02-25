# Bank Transaction Fraud Detection

## 📌 Objective

Detect fraudulent transactions in banking systems to prevent financial fraud and enhance security.

## 🛠️ Techniques Used

Machine Learning Classification Models:

Logistic Regression

Decision Trees

Random Forest

XGBoost

Neural Networks

## 🎯 Use Case

This project helps banks and financial institutions identify suspicious transactions and mitigate fraudulent activities, ensuring secure financial transactions.

## 🔍 Implementation

### 1️⃣ Data Collection & Cleaning

Preprocessed financial transaction data.

Removed null values and handled imbalanced classes using techniques like SMOTE.

### 2️⃣ Exploratory Data Analysis (EDA) & Visualization

Used histograms and correlation heatmaps to identify fraud patterns.

Visualized transaction distributions to detect anomalies.

### 3️⃣ Feature Engineering

Created new features such as:

Transaction frequency per user.

Customer spending behavior over time.

Time-based transaction patterns.

### 4️⃣ Model Implementation

Implemented multiple classifiers to classify transactions as fraudulent or legitimate.

Compared different models based on performance metrics.

### 5️⃣ Performance Evaluation

Evaluated models using:

Accuracy

Precision-Recall Score

ROC-AUC Curve

Confusion Matrix

## 📝 Results

The best-performing model was selected based on precision, recall, and AUC-ROC scores.

Feature importance analysis highlighted key factors contributing to fraudulent transactions.

## 🚀 How to Use

Clone the repository.

Install dependencies using pip install -r requirements.txt.

Run the Jupyter Notebook bank-transaction-fraud-detection.ipynb.

Analyze model performance and predictions.

## 📁 Files & Directories

data/ : Contains raw and processed datasets.

notebooks/ : Jupyter notebooks with analysis and modeling.

models/ : Saved trained models.



