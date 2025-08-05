# 🚢 Titanic Dataset - Data Cleaning & Preprocessing

## 📌 Objective

This project focuses on cleaning and preprocessing the Titanic dataset to make it ready for machine learning models. The aim is to transform raw data into a structured and usable format for predictive analysis, especially for survival classification.

---

## 🧰 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn (for optional data visualization)
- Scikit-learn (`LabelEncoder`, `StandardScaler`)

---

## 🔍 What We Did (Step-by-Step)

### 1. Loaded the Dataset
- Read the Titanic dataset using Pandas
- Explored structure, missing values, and data types

### 2. Handled Missing Values
- `Age`: Filled with **median** value
- `Embarked`: Filled with **mode** value
- `Cabin`: Dropped due to **77% missing values**

### 3. Dropped Irrelevant Columns
- Removed `Name` and `Ticket` as they do not provide meaningful value in basic models

### 4. Encoded Categorical Features
- Used **LabelEncoder**:
  - `Sex`: male → 0, female → 1
  - `Embarked`: C → 0, Q → 1, S → 2

### 5. Standardized Numerical Features
- Applied `StandardScaler` to:
  - `Age`
  - `Fare`
  - `SibSp`
  - `Parch`
- This ensures consistent scaling across features

### 6. Handled Outliers (Optional Step)
- Used **boxplots** to visualize outliers in numerical features
- Applied **Interquartile Range (IQR)** method to detect and remove outliers for `Age` and `Fare`:
  - Calculated Q1 and Q3
  - Removed rows outside the range `[Q1 - 1.5 * IQR, Q3 + 1.5 * IQR]`

### 7. Saved the Cleaned Dataset
- Final cleaned dataset saved as: `Titanic_Cleaned_LabelEncoded.csv`

---


## ✅ Outcome

After preprocessing, the dataset:
- Has no missing values
- Categorical variables are numerically encoded
- Numerical features are standardized
- Is fully ready for model training using classification algorithms

---
