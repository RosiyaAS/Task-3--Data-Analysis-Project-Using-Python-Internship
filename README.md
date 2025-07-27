# Task-3 Data-Analysis-Project-Using-Python-Internship
🎯 Customer Segmentation with K-Means Clustering
This project focuses on customer segmentation using K-Means clustering on a mall customer dataset. The goal is to group customers based on demographic and purchasing behavior to guide targeted marketing strategies.

📁 Dataset:

Source: Mall_Customers.csv

Features Used:

Age

Gender

Annual Income (k$)

Spending Score (1-100)

🔧 Process Overview:

Data Loading & Inspection:

Checked for shape, nulls, duplicates, and datatypes

Summary statistics explored for distribution

Preprocessing:

Encoded Gender feature

Dropped CustomerID

Scaled features using StandardScaler

Clustering:

Used Elbow Method to identify optimal number of clusters

Verified using Silhouette Score

Applied KMeans Clustering with optimal k=5

Visualization:

2D PCA Scatter Plot

Pair Plot of Clustered Features

3D Scatter Plot using Plotly

Elbow Plot for WCSS

Cluster Centroid visualization

🔍 Insights & Recommendations:

Cluster 2: Young high spenders – Ideal for premium product promotions

Cluster 4: Older customers with high income but low spending – Target with loyalty programs

Cluster 1: Average income & moderate spending – Use seasonal offers

Cluster 0 & 3: Low-income segments – Focus on budget-friendly or entry-level products

💾 Output:

Clustered dataset saved as segmented_customers.csv

Visual reports for interpretation and marketing strategy

📌 Technologies Used:

Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly

Scikit-learn (KMeans, PCA, StandardScaler)
