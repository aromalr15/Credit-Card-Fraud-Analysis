# 💳 Credit Card Fraud Detection Using Machine Learning and Power BI

## 📌 Project Overview

Credit card fraud is one of the major challenges in digital financial transactions. Identifying suspicious transactions accurately is important for reducing financial losses and improving transaction security.

This project focuses on developing a machine learning-based system to identify potentially fraudulent credit card transactions. Using Python, the project involves data cleaning, exploratory data analysis, feature preprocessing and machine learning classification to distinguish fraudulent transactions from legitimate ones.

An interactive Power BI dashboard is also developed to analyse fraud patterns, monitor transaction trends and visualise model performance, providing meaningful insights into transaction behaviour.

## 🎯 Project Objectives

- Analyse credit card transaction patterns and identify suspicious activities.
- Perform data cleaning and preprocessing to prepare the dataset.
- Conduct exploratory data analysis (EDA) to understand fraud distribution.
- Develop a machine learning classification model to detect fraudulent transactions.
- Evaluate model performance using Accuracy, Precision, Recall, F1 Score and Confusion Matrix.
- Build an interactive Power BI dashboard for fraud analysis and model evaluation.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Programming and model development |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib | Data visualisation |
| Seaborn | Exploratory data analysis |
| Scikit-learn | Machine learning and model evaluation |
| Power BI | Interactive dashboard development |
| DAX | Calculated measures and dashboard analytics |

## 📂 Data Source

The project uses a credit card fraud detection dataset named `credit_card_fraud_detection_2026.csv`.

**Dataset Overview:**

- Total Records: 100,000 transactions
- Total Features: 43 columns
- Fraudulent Transactions: 2,055
- Legitimate Transactions: 97,945
- Target Variable: `is_fraud`

The dataset contains transaction details, customer information, geographical indicators and risk-related features.

**Target Variable:**
- `0` – Legitimate Transaction
- `1` – Fraudulent Transaction

*Note: Add the original dataset source URL or provider name here if available. Do not claim the dataset is from a particular public platform unless verified.*

## ✨ Key Features

### 1. Data Cleaning and Preprocessing
- Identifying and handling missing values.
- Checking duplicate records.
- Converting columns into appropriate data types.
- Preparing numerical and categorical features for machine learning.

### 2. Exploratory Data Analysis (EDA)
- Analysing fraudulent versus legitimate transactions.
- Exploring transaction amount distributions.
- Identifying fraud trends over time.
- Analysing fraud across merchant categories and geographical locations.
- Understanding relationships between transaction features.

### 3. Machine Learning
- Preparing training and testing datasets.
- Selecting relevant features for classification.
- Training machine learning classification models.
- Generating fraud predictions.
- Evaluating model performance using classification metrics.

### 4. Interactive Power BI Dashboard

**Fraud Overview Dashboard**
- Total transaction count.
- Total fraudulent transactions.
- Fraud percentage.
- Recorded fraud losses.
- Fraud trends over time.
- Fraud distribution by merchant category and country.
- Interactive date, transaction channel and merchant category filters.

**Model Performance Dashboard**
- Test transaction count.
- Precision, Recall and F1 Score.
- Confusion Matrix.
- Transaction-level prediction analysis.
- Actual versus predicted fraud comparison.

## 📊 Project Workflow

1. Data collection and understanding
2. Data cleaning and preprocessing
3. Exploratory Data Analysis
4. Feature selection and preparation
5. Machine learning model development
6. Model evaluation
7. Fraud prediction generation
8. Power BI dashboard development

## 📁 Project Structure

```text
Credit-Card-Fraud-Detection/
│
├── data/
│   ├── cleaned_transactions.csv
│   └── transaction_predictions.csv
│
├── notebooks/
│   └── fraud_detection.ipynb
│
├── dashboard/
│   ├── fraud_detection_dashboard.pbix
│   └── screenshots/
│
├── README.md
└── requirements.txt
```

## 💡 Key Learnings

- Practical experience in data cleaning and preprocessing.
- Understanding and analysing imbalanced datasets.
- Applying machine learning classification techniques.
- Evaluating classification models using different performance metrics.
- Building interactive dashboards using Power BI and DAX.
- Translating data analysis results into meaningful business insights.

## 🚀 Future Improvements

- Experimenting with additional machine learning algorithms.
- Improving model performance through hyperparameter tuning.
- Developing real-time fraud monitoring capabilities.
- Integrating automated fraud alerts.
- Exploring advanced anomaly detection techniques.

## 👨‍💻 Author

**Aromal**

Data Science | Python | Machine Learning | Power BI

## ⚠️ Disclaimer

This project is developed for educational and portfolio purposes. The model is an analytical prototype and is not intended for direct deployment in real-world financial transaction systems.
