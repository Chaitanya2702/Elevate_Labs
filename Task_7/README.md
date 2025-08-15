# Task 6 - Support Vector Machines (SVM) Classification

## 📌 Objective
The goal of this task is to **implement Support Vector Machines (SVM)** for **linear** and **non-linear classification**.  
We will also visualize decision boundaries, tune hyperparameters, and evaluate performance using cross-validation.

---

## 🛠 Tools & Libraries
- **Python 3.x**
- **Scikit-learn** – For SVM models and dataset loading
- **NumPy** – For numerical operations
- **Matplotlib** – For data visualization

---

## 📂 Dataset
We use the **Breast Cancer dataset** from `sklearn.datasets`.  
This is a binary classification dataset with features related to tumor measurements, used to classify tumors as **benign** or **malignant**.

---

## 📋 Steps Followed

### 1️⃣ Load and Prepare Dataset
- Load dataset from `sklearn.datasets`.
- Split into training and testing sets.
- Standardize features for better SVM performance.

### 2️⃣ Train SVM with Linear Kernel
- Use `SVC(kernel='linear')` to train a linear classifier.
- Fit the model to training data.
- Make predictions and evaluate accuracy.

### 3️⃣ Train SVM with RBF Kernel
- Use `SVC(kernel='rbf')` for non-linear classification.
- Fit the model and compare results with the linear kernel.

### 4️⃣ Visualize Decision Boundary (2D Data)
- For demonstration, select **two features** from the dataset.
- Plot decision boundaries for both **linear** and **RBF** kernels.

### 5️⃣ Hyperparameter Tuning
- Use `GridSearchCV` to tune parameters like **C** (regularization) and **gamma** (RBF kernel parameter).
- Select the best model based on accuracy.

### 6️⃣ Cross-Validation
- Perform **k-fold cross-validation** to evaluate the model’s generalization performance.

---

## 📊 Results
- **Linear Kernel** performs well when data is linearly separable.
- **RBF Kernel** handles complex non-linear patterns better.
- Hyperparameter tuning significantly improves model accuracy.

---
