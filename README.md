# Financial Health Prediction Using Machine Learning

## 📌 Project Overview

Financial health is influenced by a combination of demographic, business, financial, and behavioral factors. This project explores these factors and develops machine learning classification models to predict financial health outcomes using survey data.

The project combines **exploratory data analysis, statistical hypothesis testing, feature preprocessing, and supervised machine learning** to understand the factors associated with financial health and evaluate how accurately financial health categories can be predicted.

The analysis is designed to answer two main questions:

1. **Which demographic, financial, and business characteristics are associated with financial health?**
2. **Can machine learning models accurately predict an individual's financial health category from the available characteristics?**

---

## 🎯 Objectives

The main objectives of this project are to:

- Clean and standardize survey data for analysis.
- Explore demographic, financial, and business characteristics.
- Analyze relationships between numerical variables.
- Identify categorical variables significantly associated with the target outcome.
- Compare financial characteristics across financial health groups.
- Transform financial values into a common USD currency.
- Assess multicollinearity among numerical predictors using Variance Inflation Factor (VIF).
- Build and compare multiple machine learning classification models.
- Evaluate model performance using classification metrics.
- Identify potential insights that could support financial inclusion and decision-making.

---

## 📊 Dataset

The project uses survey data containing information about individuals and their businesses across several countries in Southern Africa.

The dataset includes variables relating to:

- Demographics
- Personal income
- Business turnover
- Business characteristics
- Financial products and services
- Insurance
- Banking
- Loans and credit
- Financial record keeping
- Cash-flow challenges
- Tax compliance
- Financial attitudes and behaviors
- Financial health (`Target`)

The original dataset is included in this repository as:

`financial_health.csv`

> **Note:** The interpretation of the `Target` variable should follow the definition provided with the original dataset/source. The machine learning models predict the observed target categories; they do not independently define what constitutes financial health.

---

## 🛠️ Technologies & Libraries

### Programming Language
- Python 3.12

### Data Analysis
- Pandas
- NumPy
- SciPy

### Data Visualization
- Matplotlib
- Seaborn

### Statistical Analysis
- Chi-square test of independence
- Kruskal-Wallis H test
- Spearman rank correlation
- Variance Inflation Factor (VIF)

### Machine Learning
- Scikit-learn
- Statsmodels
- XGBoost

### Development Environment
- Jupyter Notebook
- VS Code
- Git & GitHub

---

## 🔄 Project Workflow

```text
Raw Survey Data
       ↓
Data Quality Assessment
       ↓
Data Cleaning & Standardization
       ↓
Missing Value Treatment
       ↓
Currency Conversion
       ↓
Exploratory Data Analysis
       ↓
Statistical Hypothesis Testing
       ↓
Multicollinearity Assessment
       ↓
Feature Encoding & Scaling
       ↓
Train/Test Split
       ↓
Machine Learning Classification
       ↓
Model Evaluation & Comparison
       ↓
Interpretation
