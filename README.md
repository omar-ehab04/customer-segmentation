# Customer Segmentation using K-Means Clustering

This project focuses on segmenting customers based on their annual income and spending score using K-Means clustering

## Project Goal

The main objective of this project is to group customers into distinct segments to gain insights into different customer behaviors and characteristics. These segments can then be used for targeted marketing strategies and personalized customer experiences.

## Dataset

The dataset used for this project is `Mall_Customers.csv`, which contains information about mall customers, including:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Key Findings

* The data was explored to understand the distribution of 'Annual Income (k$)' and 'Spending Score (1-100)'.
* K-Means clustering was applied to the scaled 'Annual Income (k$)' and 'Spending Score (1-100)' features.
* The elbow method was used to determine an optimal number of clusters.
* The resulting clusters and their decision boundaries were visualized to illustrate the customer segments.

## Steps Taken

1. **Data Loading and Exploration**: Loaded the dataset and performed initial data exploration to understand its structure and characteristics.
2. **Feature Selection**: Selected 'Annual Income (k$)' and 'Spending Score (1-100)' as the features for clustering.
3. **Data Scaling**: Scaled the selected features using `StandardScaler` to ensure equal contribution from each feature during clustering.
4. **K-Means Clustering**: Applied the K-Means algorithm to the scaled data to create customer clusters.
5. **Elbow Method**: Used the elbow method to determine the optimal number of clusters by analyzing the distortion for different numbers of clusters.
6. **Visualization**: Visualized the clusters and their decision boundaries using scatter plots and contour plots.
