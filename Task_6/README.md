# 📊 K-Nearest Neighbors (KNN) Classification

## 📌 Objective
The goal of this project is to **understand and implement the K-Nearest Neighbors (KNN)** algorithm for classification problems using Python's **Scikit-learn** library.

---

## 🛠 Tools & Libraries Used
- **Python 3.x**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Scikit-learn** – KNN model, evaluation metrics, dataset
- **Matplotlib & Seaborn** – Data visualization

---

## 📂 Dataset
- **Iris Dataset** from `sklearn.datasets`.
- Features:
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width
- Target: **Species** (Setosa, Versicolor, Virginica)

---

## 🚀 Steps Followed

1. **Load & Explore Dataset**
   - Used `load_iris()` to load dataset into a Pandas DataFrame.
   - Checked shape, sample rows, and class distribution.

2. **Feature Normalization**
   - Applied **StandardScaler** to scale features since KNN is distance-based.

3. **Train-Test Split**
   - Split dataset into **80% training** and **20% testing**.

4. **Model Building**
   - Implemented **KNeighborsClassifier** from Scikit-learn.
   - Experimented with different values of **K** (1 to 15) to find the best accuracy.

5. **Model Evaluation**
   - **Accuracy Score**
   - **Confusion Matrix**
   - **Classification Report** (Precision, Recall, F1-score)

6. **Visualization**
   - Plotted **decision boundaries** (for 2D feature space).
   - Accuracy trends with different **K values**.

---

## 📈 Results
- **Best K value**: (Based on experiment)
- **Highest Accuracy**: (Value)
- Confusion Matrix and classification report provided in notebook.

---
