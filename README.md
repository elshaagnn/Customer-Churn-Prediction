# Customer Churn Prediction

## Project Overview
This project aims to analyze customer churn patterns and develop machine learning models to predict customers who are likely to stop using a telecommunications service.

By identifying potential churn customers and understanding the factors associated with churn, businesses can develop more effective customer retention strategies.

## Business Problem
Customer churn is a major challenge for telecommunications companies. Losing customers can affect revenue and business growth.

This project uses historical customer data to identify churn patterns, evaluate predictive models, and provide actionable business recommendations.

## Project Objectives
- Analyze customer churn patterns and behavior.
- Identify factors associated with customer churn.
- Build and compare machine learning classification models.
- Evaluate model performance using classification metrics.
- Provide business recommendations to support customer retention.

## Dataset
**Dataset:** IBM Telco Customer Churn

**Source:** [Kaggle – Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

- Original records: 7,043 customers
- Records after cleaning: 7,032 customers
- Target variable: `Churn` (Yes/No)
- Features: Customer demographics, account information, subscribed services, and payment details.

## Tools & Technologies
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- SciPy
- Google Colab

## Project Workflow

### 1. Data Understanding
Explored the dataset structure, data types, customer characteristics, and churn distribution.

### 2. Data Cleaning
- Converted `TotalCharges` into numeric format.
- Handled missing values.
- Removed 11 records with missing values.

### 3. Exploratory Data Analysis (EDA)
Analyzed churn patterns based on:
- Contract type
- Customer tenure
- Monthly charges
- Customer distribution

### 4. Statistical Analysis
Applied statistical tests to examine relationships and differences between customer groups.

- Chi-Square Test
- Mann-Whitney U Test

### 5. Data Preprocessing
- Separated features and target variables.
- Split data into training and testing sets.
- Applied missing value imputation, encoding, and feature scaling.

### 6. Model Development
Developed and compared three classification models:
- Logistic Regression
- Decision Tree
- Random Forest

### 7. Model Evaluation
Evaluated model performance using:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC
- Confusion Matrix

### 8. Threshold Analysis & Feature Importance
Analyzed different classification thresholds and examined Logistic Regression coefficients to identify important churn-related features.

## Model Performance

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 73.8% | 50.4% | 78.3% | 61.4% | 0.841 |
| Decision Tree | 72.8% | 48.8% | 48.1% | 48.5% | 0.650 |
| Random Forest | 78.3% | 61.8% | 47.6% | 53.8% | 0.822 |

## Key Findings
- Logistic Regression achieved the highest recall of 78.3%, making it effective at identifying customers who are likely to churn.
- Random Forest achieved the highest accuracy of 78.3% and precision of 61.8%.
- Contract type showed a statistically significant association with customer churn.
- Customer tenure and monthly charges were also examined as potential churn-related factors.

## Business Recommendations
- Encourage customers to subscribe to long-term contracts.
- Develop targeted retention campaigns for month-to-month customers.
- Prioritize high-risk customers for proactive engagement.
- Review pricing strategies to improve customer retention.
- Use churn prediction results to support data-driven retention decisions.



## Conclusion
This project demonstrates how machine learning can be applied to customer churn prediction.

Among the evaluated models, Logistic Regression achieved the highest recall of 78.3% and ROC-AUC of 0.841. These results provide a useful foundation for identifying potential churn customers and supporting customer retention strategies.

---

**Project Category:** Machine Learning | Classification | Predictive Analytics
