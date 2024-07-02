# Customer Segmentation using K-means Clustering
This repository contains an implementation of a K-means clustering algorithm to group customers of a retail store based on their purchase history. The goal is to segment customers into distinct groups to better understand their behavior and tailor marketing strategies accordingly.

## Introduction
Customer segmentation is a crucial task for any retail business aiming to understand its customer base and improve targeting of marketing efforts. By analyzing purchase history, we can group customers into clusters with similar buying patterns.

## Data
The dataset should include the following columns (these are examples and can be adjusted based on available data):<br>

customer_id: Unique identifier for each customer.<br>
total_purchase_amount: Total amount spent by the customer.<br>
number_of_purchases: Total number of purchases made by the customer.<br>
average_purchase_value: Average value of each purchase.<br>
purchase_frequency: Frequency of purchases over a specified period.<br>

## Model
The K-means clustering algorithm is implemented using the scikit-learn library. The number of clusters (k) can be specified as a parameter. The features used for clustering include various metrics derived from purchase history.

## Results
After performing clustering, the script outputs the following: <br>

Cluster centroids representing the average values for each feature within each cluster.<br>
Visualization of the clusters (if applicable).<br>
Summary statistics for each cluster.<br>
