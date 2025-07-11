# User Profiling through Financial Data Clustering

This project explores customer financial behavior through data analysis and segmentation. Using K-Means clustering and visual exploration, customers are grouped based on income, deposits, loan usage, and account activity.

---

## 📌 Project Overview

- 🔍 Univariate and categorical analysis (Occupation, Nationality, etc.)
- 📊 Correlation heatmaps for numerical financial data
- 📈 User segmentation using K-Means clustering
- 📦 Data preprocessing and PCA for visualization
- 🎯 Customer segment labeling based on financial traits

---

##  Tools & Technologies

- Python (Pandas, NumPy)
- Seaborn & Matplotlib (for visualization)
- Scikit-learn (for KMeans and PCA)
- Microsoft Excel
- Sql,MySql
- Jupyter Notebook

---

##  Key Components

### 1. Univariate & Categorical Analysis
- Top 10 customer occupations by frequency
- Countplots and bar plots of categorical features
- Analysis by customer nationality

### 2. Numerical Insights
- Explored variables: income, credit card balance, savings, loans, etc.
- Correlation heatmap reveals strong relationships (e.g., savings ↔ deposits)

### 3. Dimensionality Reduction (PCA)
- PCA used to compress 9 financial features into 2 components
- Enabled visual 2D clustering for easier understanding

### 4. Customer Segmentation (K-Means)
- Chose optimal `K=3` using the Elbow Method
- Created segments like:
  - **High Value Clients**
  - **Mass Market Customers**
  - **Low Engagement Users**
- Used PCA for cluster visualization
- Segments labeled for clarity

---

## 📈 Sample Visuals

- Correlation heatmap of financial metrics
- <img width="924" height="783" alt="Screenshot 2025-07-12 052132" src="https://github.com/user-attachments/assets/6c315e7c-b34b-4c37-b062-ecc93f819704" />

- PCA scatterplot showing clustered segments
- <img width="980" height="692" alt="image" src="https://github.com/user-attachments/assets/eb8dcf9d-2fcb-4695-a942-519fee36fe18" />


---
