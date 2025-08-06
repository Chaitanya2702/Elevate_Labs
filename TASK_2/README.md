# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

This project is part of a Data Science learning journey, focusing on performing **Exploratory Data Analysis (EDA)** on the classic **Titanic dataset**. EDA helps us understand the dataset by using statistical summaries and visualizations.

---

## 📌 Objective

- To analyze the Titanic dataset using various EDA techniques.
- To uncover patterns, trends, anomalies, and relationships between features.
- To make basic feature-level inferences from visualizations.

---

## 🧰 Tools & Libraries Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Plotly**

---

## 📂 Dataset

- **Source**: Titanic Dataset (Kaggle)
- **File Used**: `Titanic-Dataset.csv`

---

## 📈 Steps Performed

### 1. 🧹 Data Loading & Cleaning
- Loaded the dataset using pandas.
- Checked for null values and performed basic preprocessing.

### 2. 📊 Summary Statistics
- Calculated `mean`, `median`, `mode`, `standard deviation`, etc.
- Used `.describe()` and `.info()` to understand the data distribution.

### 3. 📉 Univariate & Bivariate Visualizations
- Countplots for **Sex**, **Pclass**, and **Embarked** vs **Survived**
- Histograms and KDE plots for **Age** and **Fare**
- Boxplots to identify **outliers**
- Scatter plots to observe the relationship between **Age** and **Fare**

### 4. 🔁 Correlation Analysis
- Generated a heatmap to visualize correlation between numerical features.

### 5. 📌 Feature-Level Inferences
- Observed that:
  - Females had higher survival rates than males.
  - Passengers in 1st class had better survival odds.
  - Younger passengers had a slightly higher chance of survival.
  - Higher fare seemed correlated with survival.

---

## 📷 Sample Visualizations

- **Countplot** – Gender vs Survival
- **Histogram** – Age and Fare Distribution
- **Boxplot** – Detecting Outliers
- **Heatmap** – Correlation between features
- **Interactive Scatter Plot** – Age vs Fare by Survival

---

