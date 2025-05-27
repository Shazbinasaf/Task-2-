# 🛳️ Titanic Dataset - Exploratory Data Analysis (EDA)

This project provides a detailed **Exploratory Data Analysis (EDA)** of the **Titanic - Machine Learning from Disaster** dataset from [Kaggle](https://www.kaggle.com/competitions/titanic/). The goal is to uncover key insights about survival patterns among passengers.

---

## 📁 Dataset

- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)
- Files used:
  - `train.csv` — Main dataset for analysis.

---

## 📊 EDA Overview

The EDA script performs:

### ✅ Basic Data Exploration
- Loading dataset with `pandas`
- Checking dataset info, missing values, and statistics

### ✅ Univariate Analysis
- Passenger survival count
- Gender distribution
- Age distribution
- Embarkation port count

### ✅ Bivariate/Multivariate Analysis
- Survival vs Gender
- Survival vs Passenger Class (`Pclass`)
- Survival vs Fare
- Survival vs Embarkation Port
- Boxplots (Age vs Class)

### ✅ Correlation Analysis
- Heatmap to understand relationships between numerical features

---

## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`

Install the libraries (if not already installed):

```bash
pip install pandas numpy seaborn matplotlib
