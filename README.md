# 🛍️ Customer Segmentation using Clustering Algorithms

This project demonstrates how to apply various clustering techniques for customer segmentation using the **Mall Customers dataset**. Clustering allows businesses to identify distinct customer groups and better understand their spending habits, which can lead to more personalized marketing and business strategies.

---

## 📂 Dataset

The dataset `Mall_Customers.csv` contains information about 200 customers including:
- `CustomerID`
- `Gender`
- `Age`
- `Annual Income (k$)`
- `Spending Score (1-100)`

---

## 🧰 Technologies & Libraries Used

- **Python 3.x**
- **Pandas** – for data handling
- **NumPy** – numerical operations
- **Matplotlib & Seaborn** – data visualization
- **Scikit-learn** – for preprocessing and clustering models
- **SciPy** – for hierarchical clustering

---

## 📊 Clustering Techniques Implemented

### 1. K-Means Clustering
- Uses the Elbow Method to determine the optimal number of clusters.
- Visualizes customer segments based on Annual Income and Spending Score.

### 2. Hierarchical Clustering
- Uses dendrograms for visualizing merge distances.
- Performs Agglomerative Clustering using Ward linkage.

### 3. DBSCAN (Density-Based Spatial Clustering)
- Detects arbitrary-shaped clusters and outliers using density measures.

### 4. MeanShift Clustering
- Automatically detects the number of clusters using bandwidth estimation.

---

## 🧪 Steps Performed

1. **Data Preprocessing**
   - Checked for null/duplicate values.
   - Dropped unnecessary columns (`CustomerID`).
   - Encoded categorical features using `LabelEncoder`.
   - Scaled numerical features with `StandardScaler`.

2. **Exploratory Data Analysis (EDA)**
   - Used pairplots to visualize relationships among features.

3. **Modeling & Visualization**
   - Applied and visualized results from all four clustering algorithms.

---

## 📈 Results

- Each clustering method revealed different customer groupings.
- K-Means and Hierarchical methods provided clearer segmentation on Annual Income vs. Spending Score.
- DBSCAN was useful in identifying noise/outliers.
- MeanShift detected cluster centers automatically but with higher computational cost.

---
