# 🧩 Customer Segmentation using K-Means Clustering

This project applies **K-Means Clustering** to the Mall Customer Segmentation dataset to group customers based on their **Annual Income** and **Spending Score**. The clustering helps businesses identify distinct customer groups and target them with personalized strategies.

---

## 📌 Project Workflow

### 1. Import Libraries
We use the following libraries:
- **pandas** → Data handling
- **matplotlib** → Data visualization
- **scikit-learn** → K-Means clustering, PCA, Silhouette Score

---

### 2. Load Dataset
The dataset `Mall_Customers.csv` contains:
- **CustomerID**  
- **Gender**  
- **Age**  
- **Annual Income (k$)**  
- **Spending Score (1–100)**  

We select **Annual Income** and **Spending Score** for clustering.

---

### 3. Elbow Method
To determine the optimal number of clusters **K**, we plot the **Elbow Curve** by calculating **Inertia** (Within-Cluster Sum of Squares) for K = 1 to 10.

---

### 4. Fit K-Means
- Chose **K=5** (from Elbow curve).  
- Trained the **KMeans model** and assigned **cluster labels** to each customer.

---

### 5. Visualize Clusters
Scatter plot of:
- **X-axis**: Annual Income  
- **Y-axis**: Spending Score  
- Colors represent different clusters.  
- Red “X” marks indicate cluster centroids.  

---

### 6. Evaluate Clustering
We compute the **Silhouette Score** to measure clustering quality:
- **+1** → Well separated clusters  
- **0** → Overlapping clusters  
- **-1** → Wrongly assigned clusters  

---

### 7. PCA (Optional)
To visualize **high-dimensional data**, we applied **PCA (Principal Component Analysis)** and reduced 3 features (Age, Income, Score) to 2 dimensions for plotting.

---

## 📊 Results
- **Optimal K**: 5  
- **Silhouette Score**: ~0.55 (varies depending on dataset split)  
- Distinct groups of customers identified:
  1. High income, high spenders  
  2. High income, low spenders  
  3. Medium income, balanced spending  
  4. Low income, high spenders  
  5. Low income, low spenders  

---