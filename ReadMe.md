# 🏦 Bank Churn Prediction

This project aims to predict whether a customer will churn (i.e., leave the bank) using historical data on customer demographics, credit card usage, and account activity. The goal is to help financial institutions proactively identify at-risk customers and take action to retain them.

---

## 📁 Dataset

- **Source**: `BankChurners.csv`
- **Target Variable**: `Attrition_Flag` (binary: 1 = Attrited Customer, 0 = Existing Customer)
- **Features**: Includes customer age, credit limit, transaction counts, and more.

---

## 🔍 Project Scope

### Objectives
- Clean and preprocess the dataset
- Explore and visualize key patterns
- Build a logistic regression model to predict churn
- Address class imbalance using class weighting and SMOTE
- Evaluate model performance using precision, recall, F1-score, and ROC-AUC

---

## 🧪 Methodology

1. **Data Preprocessing**
   - Handled missing values and duplicates
   - Encoded categorical variables
   - Scaled features for model convergence

2. **Exploratory Data Analysis (EDA)**
   - Visualized churn distribution and feature relationships
   - Identified class imbalance

3. **Modeling**
   - Trained logistic regression with and without class balancing
   - Applied SMOTE to oversample the minority class
   - Evaluated using classification metrics and ROC curve

---

## 📊 Results

- Achieved **85% recall** on attrited customers after applying SMOTE
- Balanced performance with an F1-score of **0.65** for the minority class
- Identified key features influencing churn

---

## 🚀 Future Work

- Experiment with tree-based models (Random Forest, XGBoost)
- Perform hyperparameter tuning
- Deploy the model as an API or dashboard

---

## 📌 Requirements

- Python 3.8+
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- imbalanced-learn

---

## 📬 Contact

Created by [Omar Orabi](https://github.com/Omar-Orabi97) — feel free to reach out with questions or suggestions!