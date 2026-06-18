# Customer Segmentation Analysis — K-Means Clustering

## Overview
An unsupervised machine learning project using K-Means clustering 
to segment mall customers based on annual income and spending score, 
helping identify the most valuable customer groups for targeted marketing.

## Questions Explored
- What is the distribution of customer age, income and spending score?
- Is there a relationship between annual income and spending score?
- What is the optimal number of customer segments?
- What are the characteristics of each customer segment?
- Which customer segment should the mall target most?

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (KMeans, StandardScaler)
- Jupyter Notebook

## Dataset
- Mall_Customers.csv (sourced from Kaggle)
- 200 mall customer records

## Model Details
- Algorithm: K-Means Clustering
- Optimal Clusters: 5 (determined by Elbow Method)
- Features Used: Annual Income, Spending Score

## Customer Segments Identified
1. High Income High Spenders — Prime targets for premium marketing
2. Low Income High Spenders — Loyal and engaged customers
3. Average Income Average Spenders — Largest segment, growth potential
4. High Income Low Spenders — Untapped opportunity segment
5. Low Income Low Spenders — Budget conscious customers

## Key Insights
- 5 distinct customer segments were identified
- Annual income alone does not predict spending behavior
- High Income High Spenders are the most valuable segment
- High Income Low Spenders represent an untapped opportunity
- Younger customers between 20-40 dominate the customer base

## Author
Marvis Obanor
