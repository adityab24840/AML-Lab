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
```

## Getting Started

To get started with this project, follow the steps below:

1. **Clone the Repository or Download the Dataset:** Clone this repository to your local machine or download the `Mall_Customers.csv` dataset from the repository.

2. **Run the Python Script:** Execute the provided Python script, `customer_segmentation.py`. This script automates the entire process, from reading the data to visualizing the clustered results.

3. **Data Exploration and Analysis:** The script first reads the data from the dataset and performs exploratory data analysis (EDA) to understand its structure and attributes.

4. **Visualization of Data Distribution:** The script includes a scatter plot of 'Annual Income' vs 'Spending Score' for initial data exploration. This visualization provides insights into potential patterns in customer behavior.

5. **Applying K-Means Clustering:** The K-Means clustering algorithm is then applied to segment the customers based on their 'Annual Income' and 'Spending Score'. The elbow method and silhouette score are used to identify the optimal number of clusters.

6. **Visualizing Clusters:** The script concludes by visualizing the clustered customers using a scatter plot. Each cluster is differentiated by a distinct color, helping to identify different customer segments.

By following these steps, you can understand the process of customer segmentation using K-Means clustering and gain insights into the distinct customer segments present in the dataset.

**Results**

The results of the customer segmentation will be displayed through various visualizations:

1. Scatter plot of 'Annual Income' vs 'Spending Score' for initial data exploration.
2. Elbow method plot to identify the optimal number of clusters.
3. Silhouette score plot to further validate the optimal cluster count.
4. Scatter plot of clustered customers based on 'Annual Income' and 'Spending Score', colored by cluster.

**Conclussion**
Customer segmentation helps businesses gain insights into different customer groups and tailor marketing strategies accordingly. This project showcases the process of using K-Means clustering for customer segmentation and provides visualizations to aid in understanding the results.