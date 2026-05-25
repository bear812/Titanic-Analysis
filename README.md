---
# Titanic Dataset Analytics & Predictive Modeling

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Machine_Learning-Scikit--Learn-orange.svg)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

An end-to-end data science and machine learning project exploring passenger survival patterns on the Titanic. This repository covers exploratory data analysis (EDA), data cleaning, feature engineering, and the deployment of a Logistic Regression classifier to predict survival outcomes.

---

## 📌 Project Overview
The objective of this project is to analyze the classic Titanic dataset to determine what sorts of people were most likely to survive (e.g., gender, age, socio-economic class) and to construct a predictive model utilizing a supervised machine learning framework.

### Key Highlights
* **Dynamic Imputation:** Age missing variables are handled cleanly using group-by logic based on matching `Sex` and `Pclass` cohorts instead of global averages.
* **Feature Engineering:** Extracted `FamilySize` to capture the underlying correlations between traveling with family and survival probability.
* **Evaluation Metrics:** Achieved solid baseline classification metrics evaluated via Confusion Matrices and precision-recall trade-offs.

---

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn

---

## 📂 Repository Structure
```text
├── Titanic.csv              # The raw passenger dataset
├── titanic_analytics.ipynb  # Main Jupyter Notebook implementation
├── README.md                # Project documentation
└── requirements.txt         # Required Python packages
## 📌 Project Overview
The objective of this project is to analyze the classic Titanic dataset to determine what sorts of people were most likely to survive (e.g., gender, age, socio-economic class) and to construct a predictive model utilizing a supervised machine learning framework.

### Key Highlights
* **Dynamic Imputation:** Age missing variables are handled cleanly using group-by logic based on matching `Sex` and `Pclass` cohorts instead of global averages.
* **Feature Engineering:** Extracted `FamilySize` to capture the underlying correlations between traveling with family and survival probability.
* **Evaluation Metrics:** Achieved solid baseline classification metrics evaluated via Confusion Matrices and precision-recall trade-offs.

---

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-learn

---

