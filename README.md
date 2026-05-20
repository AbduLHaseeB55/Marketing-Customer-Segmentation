# 🎯 Marketing Analytics: Unsupervised Customer Segmentation

## 🎯 Business Objective
Mass marketing is inefficient. This project uses Unsupervised Machine Learning to discover hidden demographic patterns within a database of 45,000 bank customers, allowing for highly personalized, high-ROI advertising campaigns.

## 📊 Engineering Insights
* **The Elbow Method:** Mathematically determined the optimal number of segments (4) using WCSS variance analysis.
* **Feature Scaling:** Applied StandardScaler to ensure financial metrics like "balance" didn't overpower demographic metrics like "age".

## 🤖 Machine Learning Engine
* **Algorithm:** K-Means Clustering
* **Evaluation:** Silhouette Score for cluster separation integrity.
* **Output:** 4 distinct Marketing Personas with specific financial profiles.

## 🛠️ Tech Stack
* **Python** (Pandas, Scikit-Learn)
* **Visualization:** Seaborn, Matplotlib
