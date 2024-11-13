# AdventureWorks Sales Data Analysis

This repository contains an analysis of the AdventureWorks Sales dataset (121,253 transactions from 2017 to 2020). The focus is on customer segmentation using the **RFM model** (Recency, Frequency, Monetary) and optimizing clusters using the **WCSS (Elbow Method)**.

## Table of Contents

1. [Introduction](#introduction)
2. [Data Cleaning](#data-cleaning)
3. [Data Standardization](#data-standardization)
4. [Clustering with RFM Model](#clustering-with-rfm-model)
5. [Optimization with WCSS (Elbow Method)](#optimization-with-wcss-elbow-method)
6. [Cluster Analysis](#cluster-analysis)
7. [Segmentation Insights](#segmentation-insights)
8. [Conclusion](#conclusion)

## Introduction

The dataset used in this analysis includes 121,253 transactions from 2017 to 2020. The goal of this analysis is to segment customers based on their behavior using the **RFM model** and optimize the number of segments using the **WCSS method**.

## Data Cleaning

- Handle missing values and duplicates.
- Correct data types and formats.
- Detect and remove outliers.

## Data Standardization

- Normalize the **RFM** variables (Recency, Frequency, Monetary) using `StandardScaler` for clustering.

## Optimization with WCSS (Elbow Method)

- Use the **Elbow Method** to determine the optimal number of clusters by plotting the **WCSS (Within-Cluster Sum of Squares)**.
  
## Clustering with RFM Model

- Calculate **RFM scores** for each customer.
- Perform **K-Means clustering** to segment customers into distinct groups based on RFM values.

## Cluster Analysis

- Profile each cluster and analyze customer characteristics.
- Visualize and interpret the results of the clustering.

## Segmentation Insights

- Derive business insights for each customer segment.
- Provide recommendations for targeted marketing and sales strategies.

## Conclusion

- Summary of the key findings from the analysis.
- Potential applications of the customer segmentation for improving business strategies.

---

## Requirements

- Python 3.x
- pandas
- numpy
- sklearn
- matplotlib
- seaborn
