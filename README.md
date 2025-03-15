# Telecom Customer Churn Prediction

## Overview
In the telecom industry, customers have multiple service providers to choose from and frequently switch between operators. Given the high cost of acquiring new customers compared to retaining existing ones, customer retention has become a primary business goal. This project aims to build a predictive model to identify customers at high risk of churn and determine the key indicators that contribute to churn.

## Problem Statement
Telecom companies experience an annual churn rate of **15-25%**. Since it costs **5-10 times more** to acquire a new customer than to retain an existing one, reducing customer churn is critical. The goal of this project is to analyze customer-level data from a leading telecom firm and build machine learning models to predict customer churn.

### Customer Lifecycle Phases
1. **Good Phase:** The customer is satisfied and behaves normally.
2. **Action Phase:** The customer starts experiencing issues such as service dissatisfaction or competitive offers, altering their behavior.
3. **Churn Phase:** The customer decides to leave the service.

For this project, we use a **four-month window**:
- First two months: **Good phase**
- Third month: **Action phase**
- Fourth month: **Churn phase**

## Dataset
The dataset contains customer usage and behavioral data. The key features include:
- Customer demographics
- Call usage (incoming/outgoing minutes, international calls, etc.)
- Data usage
- Billing and payments
- Service complaints
- Contract details

## Objective
- Analyze customer behavior to identify patterns leading to churn.
- Build a **predictive model** using machine learning techniques to classify customers as potential churners.
- Provide **actionable insights** for telecom firms to retain high-value customers.

## Tools & Technologies Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, imbalanced-learn
- **Machine Learning Techniques:** Logistic Regression, Decision Trees, Random Forest, Support Vector Machines (SVM), Gradient Boosting
- **Feature Engineering & Selection:** Correlation analysis, PCA, SMOTE (for handling imbalanced data)
- **Evaluation Metrics:** Accuracy, Precision, Recall, F1-score, ROC-AUC

## Model Performance
| Model | Accuracy | F1 Score | ROC-AUC |
|--------|------------|------------|------------|
| Logistic Regression | XX% | XX | XX |
| Random Forest | XX% | XX | XX |
| XGBoost | XX% | XX | XX |
| SVM | 90.67% | 0.115 | 0.855 |

## Challenges Faced
- **Class Imbalance:** The dataset had significantly fewer churn cases, requiring resampling techniques like SMOTE.
- **Feature Selection:** Identifying the most relevant features for churn prediction.
- **Optimizing Model Performance:** Tuning hyperparameters to improve classification metrics.

## How to Use This Repository
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/telecom-churn-prediction.git
