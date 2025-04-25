# 🏦 Predicting Credit Risk for Loan Applicants

A comprehensive Exploratory Data Analysis (EDA) project to understand and visualize patterns in credit risk data for loan applicants using the **German Credit Dataset**. This project is the initial step towards building a predictive model that identifies high-risk loan applicants.

---

## 📌 Description

This project involves:

- Loading and preprocessing the German Credit Dataset.
- Performing exploratory data analysis (EDA) to gain insights into both numerical and categorical features.
- Visualizing distributions, correlations, and engineered features like age groups.
- Highlighting key trends to assist in credit risk modeling.

The aim is to understand applicant characteristics that may contribute to either good or bad credit risk and pave the way for future predictive modeling.

---

## 📁 Dataset

Dataset used: [German Credit Data]

> **Note:** The dataset used in this project does **not** contain a target variable like `Risk` or `Class`. If you're looking to build a classifier, make sure to download the version that includes the credit risk labels.

---

## 🚀 Features Explored

### ✅ Numerical Features

- Duration
- Credit Amount
- Installment Rate
- Present Residence
- Age (and Age Group)
- Number of Credits

### ✅ Categorical Features

- Sex
- Job
- Housing
- Saving Accounts
- Checking Account
- Purpose
- Age_Group (Engineered)

---

## 📊 Visualizations

The following visualizations are generated and saved:

- `numerical_histograms.png` – Histograms for numerical features
- `categorical_bars.png` – Bar charts for categorical features
- `correlation_heatmap.png` – Correlation heatmap of numerical features

---

## 📦 Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import warnings
```



## 📌 Next Steps

- Acquire labeled dataset with a target variable like `Risk`.
- Perform data cleaning and preprocessing for modeling.
- Train machine learning models (Logistic Regression, Decision Tree, etc.).
- Evaluate models using metrics like accuracy, precision, recall, and F1-score.

---

## 🤝 Contribution

Contributions are welcome! Feel free to open issues or submit pull requests for improvements, additional visualizations, or model training pipelines.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
