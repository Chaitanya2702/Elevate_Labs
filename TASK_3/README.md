# Housing Price Prediction using Linear Regression

## 📌 Objective
This project demonstrates the implementation of **Simple** and **Multiple Linear Regression** to predict housing prices based on various features.

---

## 🛠️ Tools & Libraries
- **Python 3.x**
- **Pandas** – for data manipulation
- **NumPy** – for numerical computations
- **Scikit-learn** – for machine learning model implementation
- **Matplotlib** – for data visualization

---

## 📂 Dataset
The dataset contains various features of houses such as:
- Location
- Size
- Number of bedrooms
- Number of bathrooms
- Price

### **Target Variable**
- `Price` – The selling price of the house.

### **Feature Variables**
- Numerical and categorical variables describing the house.

---

## 📋 Project Workflow

### **1. Data Loading**
- Load the dataset using `pandas.read_csv()`.
- Inspect the first few rows to understand its structure.

### **2. Data Preprocessing**
- Handle missing values if any.
- Convert categorical variables into numeric form using **One-Hot Encoding**.
  - `drop_first=True` is used to avoid multicollinearity by removing one category from each set of dummies.

### **3. Train-Test Split**
- Split the dataset into **training** (80%) and **testing** (20%) sets using `train_test_split()`.

### **4. Model Training**
- Initialize and train the **Linear Regression** model on the training data.

### **5. Model Evaluation**
- Predict prices for the test set.
- Evaluate using:
  - **Mean Absolute Error (MAE)**
  - **Mean Squared Error (MSE)**
  - **R² Score**

### **6. Visualization**
- For simple linear regression, plot the regression line against the actual values.
- Visualize residual errors if required.

### **7. Model Interpretation**
- **Intercept** → Base predicted price when all features are zero.
- **Coefficients** → Change in predicted price for a one-unit change in the feature, keeping other features constant.

---

## 🚀 How to Run
1. Install required dependencies:
   ```bash
   pip install pandas numpy scikit-learn matplotlib
