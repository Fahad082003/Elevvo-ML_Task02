Mall Customer Segmentation using K-Means
📌 Project Overview
This project applies K-Means clustering to the Mall Customer dataset (Kaggle) to segment customers into distinct groups based on Annual Income and Spending Score. This segmentation helps businesses target specific customer groups for marketing and strategy.

📂 Dataset
Source: Mall Customer Dataset - Kaggle
Features Used:

Annual Income (k$)
Spending Score (1-100)

🔍 Steps Performed
Data Loading & Exploration
Feature Selection (Annual Income & Spending Score)
K-Means Clustering
Elbow Method to determine optimal number of clusters
Visualization of clusters in 2D space with centroids

🛠 Technologies Used
Python
Pandas
Matplotlib
scikit-learn

📊 Results
Optimal Clusters: 5 (via Elbow Method)
Clear segmentation of customers based on income & spending habits
Helpful for targeted marketing strategies

🚀 How to Run
bash
Copy
Edit
pip install pandas matplotlib scikit-learn
python kmeans_mall_customers.py

📸 Sample Visualization
Scatter plot showing customer clusters with centroids

Elbow method graph to select K

