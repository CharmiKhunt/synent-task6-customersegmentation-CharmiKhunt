# Customer Segmentation Using K-Means Clustering

## Overview

This project is about grouping customers based on their income and spending habits using the K-Means Clustering algorithm.

Customer segmentation helps businesses understand different types of customers and create better marketing strategies for each group.

## Dataset

**Dataset:** Mall Customer Dataset

The dataset contains information about customers visiting a mall.

### Features

* CustomerID
* Gender
* Age
* Annual Income (k$)
* Spending Score (1–100)

For clustering, the following features were mainly used:

* Annual Income (k$)
* Spending Score (1–100)

## Steps Performed

### 1. Data Loading

The dataset was loaded into Python using Pandas.

### 2. Data Exploration

Basic information about the dataset was checked, including:

* Number of rows and columns
* Data types
* Missing values

### 3. Data Preprocessing

The required features were selected and scaled using StandardScaler so that both features have equal importance.

### 4. Finding the Optimal Number of Clusters

The Elbow Method was used to find the best value of K (number of clusters).

### 5. Applying K-Means Clustering

The K-Means algorithm was applied to divide customers into different groups based on their spending behavior and income.

### 6. Visualization

Customer groups were displayed using scatter plots to clearly see the different clusters.

## Results

The customers were divided into different groups such as:

* High Income and High Spending customers
* High Income and Low Spending customers
* Low Income and High Spending customers
* Low Income and Low Spending customers

These groups can help businesses understand customer behavior and improve marketing decisions.

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

## Project Output

* Data Preprocessing
* Elbow Method Graph
* K-Means Clustering Model
* Cluster Visualization
* Customer Segmentation Insights

## Conclusion

This project successfully used K-Means Clustering to segment customers based on annual income and spending score. The generated customer groups can help businesses identify valuable customers and plan better marketing strategies.
