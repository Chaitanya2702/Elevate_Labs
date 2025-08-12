# 🩺 Heart Disease Prediction - Decision Trees & Random Forests

This project demonstrates **tree-based classification models** — **Decision Tree Classifier** and **Random Forest Classifier** — to predict the presence of heart disease using the provided dataset (`heart.csv`).  
The workflow includes model training, overfitting analysis, feature importance interpretation, and evaluation using cross-validation.

---

## 📌 Objective
- Understand how **Decision Tree** and **Random Forest** algorithms work for classification.
- Visualize a Decision Tree.
- Analyze **overfitting** and control tree depth.
- Compare accuracy between **Decision Tree** and **Random Forest**.
- Interpret **feature importances**.
- Perform **cross-validation** for robust evaluation.

---

## 🛠 Tools & Libraries
- **Python**
- **Pandas** – Data loading and manipulation
- **NumPy** – Numerical operations
- **Scikit-learn** – Model building and evaluation
- **Graphviz** – Tree visualization
- **Matplotlib & Seaborn** – Data visualization

---

## 📂 Dataset
The dataset `heart.csv` contains patient health parameters and a target column indicating the presence (`1`) or absence (`0`) of heart disease.

**Target Column:**
- `target` → 1 = Heart disease, 0 = No heart disease

---

## 🔍 Steps Performed

### **Step 1: Load and Explore Dataset**
- Loaded `heart.csv` using Pandas.
- Checked for missing values and dataset statistics.
- Visualized data distribution.

### **Step 2: Train a Decision Tree Classifier**
- Used `DecisionTreeClassifier` from Scikit-learn.
- Trained the model on train-test split data.
- Visualized the tree using `export_graphviz` and `Graphviz`.

### **Step 3: Analyze Overfitting**
- Trained models with different `max_depth` values.
- Observed training vs. testing accuracy to detect overfitting.

### **Step 4: Train a Random Forest Classifier**
- Used `RandomForestClassifier` for better generalization.
- Compared accuracy with the Decision Tree model.

### **Step 5: Interpret Feature Importances**
- Extracted and plotted feature importances from Random Forest.

### **Step 6: Evaluate with Cross-Validation**
- Used `cross_val_score` to evaluate models on multiple folds.
- Compared average accuracy for Decision Tree and Random Forest.

---

## 📊 Results Summary
| Model                   | Accuracy (Test) | Cross-Validation Avg. Accuracy |
|-------------------------|----------------|--------------------------------|
| Decision Tree           | ~XX%           | ~XX%                           |
| Random Forest           | ~XX%           | ~XX%                           |

*(Replace `XX%` with actual results after running the notebook.)*

---

## 📈 Feature Importance Plot
The feature importance plot shows which health indicators contribute most to predicting heart disease.

---

