Customer Segmentation using DBSCAN 
📌 Project Overview
Following my K-Means project, Day 5 focuses on DBSCAN Clustering. While K-Means is great for spherical clusters, DBSCAN excels at finding clusters based on density and is robust to outliers. This project segments retail customers based on their Annual Income and Spending Score.

🛠️ Technical Stack
Libraries: Scikit-Learn, Pandas, NumPy, Seaborn.

Algorithm: DBSCAN (Density-Based Spatial Clustering of Applications with Noise).

Key Hyperparameters: eps (epsilon) and min_samples.

📊 Key Steps Implemented
Feature Selection: Isolating income and spending columns for density analysis.

Modeling: Applying the DBSCAN algorithm to identify high-density regions.

Noise Detection: Identifying data points that do not belong to any cluster (labeled as -1).

Visualization: Creating scatter plots to visualize dense customer groups vs. outliers.
