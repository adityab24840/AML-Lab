# Customer Segmentation using K-Means Clustering

This project demonstrates customer segmentation using K-Means clustering algorithm on mall customer data. The goal is to categorize customers into distinct groups based on their annual income and spending score. The visualization of the clusters helps in identifying different types of customers and can inform marketing and business strategies.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction

Customer segmentation is a crucial part of customer analysis, where customers with similar characteristics are grouped together. K-Means clustering is a common unsupervised machine learning algorithm used for segmentation.

In this project, we use Python along with libraries like pandas, numpy, matplotlib, seaborn, scikit-learn, and yellowbrick to perform customer segmentation and visualize the results.

## Prerequisites

Before running the code, ensure you have the following dependencies installed:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- yellowbrick

You can install these using the following command:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn yellowbrick

Getting Started
Clone this repository or download the Mall_Customers.csv dataset.
Run the provided Python script, customer_segmentation.py.
The script reads the data, performs exploratory data analysis (EDA), visualizes the data distribution, and then applies K-Means clustering.
The elbow method and silhouette score are used to determine the optimal number of clusters.
The final clusters are visualized along with the identified customer types.
Results
The results of the customer segmentation will be displayed through various visualizations:

Scatter plot of 'Annual Income' vs 'Spending Score' for initial data exploration.
Elbow method plot to identify the optimal number of clusters.
Silhouette score plot to further validate the optimal cluster count.
Scatter plot of clustered customers based on 'Annual Income' and 'Spending Score', colored by cluster.
Conclusion
Customer segmentation helps businesses gain insights into different customer groups and tailor marketing strategies accordingly. This project showcases the process of using K-Means clustering for customer segmentation and provides visualizations to aid in understanding the results.