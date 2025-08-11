# 📊 Logistic Regression - Binary Classification (Breast Cancer Dataset)

This project is part of a Machine Learning learning journey, focusing on building a **binary classification model** using **Logistic Regression**.  
The dataset used is the classic **Breast Cancer Wisconsin Diagnostic dataset** from Scikit-learn.  
The goal is to predict whether a tumor is **malignant** or **benign** based on cell nuclei features.

---

## 📌 Objective

- To build and evaluate a binary classifier using Logistic Regression.
- To understand the **sigmoid function** and **decision threshold tuning**.
- To evaluate the model using **confusion matrix**, **precision**, **recall**, and **ROC-AUC** score.

---

## 🧰 Tools & Libraries Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Scikit-learn**

---

## 📂 Dataset

- **Source**: Breast Cancer Wisconsin Diagnostic Dataset (from Scikit-learn)
- **Target Column**:
  - `0` → Malignant
  - `1` → Benign
- **Features**: 30 numeric features describing characteristics of cell nuclei (e.g., mean radius, mean texture, mean smoothness).

---

## 📈 Steps Performed

### 1. 🧹 Load & Explore Dataset
- Loaded dataset from Scikit-learn using `load_breast_cancer()`.
- Converted it to a Pandas DataFrame for easy handling.
- Checked shape, column names, and basic information.

### 2. ✂ Train-Test Split & Feature Scaling
- Used `train_test_split()` to split the dataset into 80% training and 20% testing sets.
- Standardized features using `StandardScaler`.

### 3. 🧠 Train Logistic Regression Model
- Initialized `LogisticRegression(max_iter=1000)`.
- Fitted the model on the scaled training set.

### 4. 📊 Model Evaluation
- Generated predictions on the test set.
- Computed **Confusion Matrix**, **Precision**, **Recall**, and **ROC-AUC** score.
- Plotted the **ROC Curve** for visualization.

### 5. 🎯 Tune Decision Threshold
- Adjusted the probability threshold from default `0.5` to `0.4` to observe changes in precision and recall.

### 6. 📈 Sigmoid Function Visualization
- Implemented a simple sigmoid function in Python.
- Plotted the sigmoid curve to understand how Logistic Regression maps linear combinations to probabilities.

---

## 📷 Sample Outputs

- **Confusion Matrix** – Shows classification results.
- **ROC Curve** – Plots True Positive Rate vs False Positive Rate.
- **Sigmoid Curve** – Visual representation of probability mapping.

---

## 📌 Observations
- The model achieved **high precision and recall** on the test data.
- ROC-AUC score was **close to 1.0**, indicating excellent performance.
- Lowering the decision threshold increased recall but reduced precision.
- The sigmoid curve clearly demonstrates how Logistic Regression outputs probabilities.

---

