# Mall-Customer-Segmentation


## Overview

This project applies unsupervised learning techniques to segment customers based on their spending habits and income. Using the Mall Customers dataset, I identify distinct customer groups through the K-Means clustering algorithm. These segments can help businesses tailor their marketing strategies to meet the specific needs of each group, ultimately improving customer satisfaction and revenue.

## Problem Statement

Retail businesses often struggle to understand their diverse customer base and effectively market to each segment. By segmenting customers into groups with similar behaviors, businesses can create targeted marketing campaigns, optimize product offerings, and improve customer engagement.

## Approach

### 1. Exploratory Data Analysis (EDA)
I begin by exploring the data to understand the distribution of features such as age, annual income, and spending score. This helps identify any patterns or trends that could influence the clustering process.

### 2. Data Preprocessing
The data is standardized to ensure that all features contribute equally to the clustering.

### 3. Clustering with K-Means
The K-Means algorithm is applied to segment the customers into distinct groups. I determine the optimal number of clusters using the Elbow Method and Silhouette Scores, and five clusters are identified as the most appropriate for this dataset.

### 4. Results
The final clusters represent different customer segments, each with unique spending behaviors. 

## Content in the Repository

- **Mall Customer Segmentation.ipynb:** The Jupyter notebook containing the full analysis, from data loading and preprocessing to clustering and interpretation of results.
- **Mall Customers Data:** Link to the dataset used for this project.
