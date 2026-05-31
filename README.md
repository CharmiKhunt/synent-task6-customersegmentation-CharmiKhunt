# synent-task6-customersegmentation-CharmiKhunt

# Customer Segmentation Using K-Means Clustering

## Problem Statement

The objective of this project is to perform **customer segmentation** using the **Mall Customer Dataset**. The aim is to group customers based on their purchasing behavior and spending patterns. By identifying different customer segments, businesses can better understand their customers and create targeted marketing strategies.

This project applies **K-Means Clustering**, an unsupervised machine learning algorithm, to divide customers into meaningful groups based on selected features.

---

## Dataset Details

**Dataset Name:** Mall Customer Dataset

**Source:** Kaggle

The dataset contains customer information collected from mall visitors.

### Features included in the dataset:

* **Customer ID** – Unique identifier for each customer
* **Gender** – Male / Female customer category
* **Age** – Age of customer
* **Annual Income (k$)** – Customer’s yearly income
* **Spending Score (1–100)** – Score assigned based on customer spending behavior

For clustering analysis, the main features used were:

* Annual Income (k$)
* Spending Score (1–100)

These features help in understanding customer purchasing habits and segmentation patterns.

---

## Approach

The project was implemented using **Python, Jupyter Notebook, Pandas, Scikit-learn, Matplotlib, and Seaborn**.

The following steps were followed:

### 1. Data Loading and Exploration

The dataset was loaded using Pandas and explored to understand dataset structure, columns, data types, and basic statistics.

### 2. Data Preprocessing

Data preprocessing steps included:

* Checking missing values
* Selecting important features for clustering
* Feature scaling using **StandardScaler**

### 3. Determining Optimal Clusters

The **Elbow Method** was applied to determine the optimal number of clusters by analyzing the WCSS (Within Cluster Sum of Squares) values.

### 4. K-Means Clustering

K-Means clustering algorithm was applied to group customers into different segments based on income and spending behavior.

### 5. Cluster Visualization

Customer clusters were visualized using scatter plots to clearly observe the separation between customer groups and identify cluster patterns.

---

## Results

The customer segmentation analysis successfully divided customers into multiple groups based on their spending behavior and annual income.

Key observations from the analysis:

* **High Income + High Spending customers** were identified as premium customers.
* **High Income + Low Spending customers** represent potential customers that businesses can target with marketing campaigns.
* **Low Income + High Spending customers** indicate customers with strong purchasing interest despite lower income.
* **Low Income + Low Spending customers** form budget-conscious customer groups.

The clustering model provided meaningful customer segments that can help businesses improve customer understanding, marketing strategies, and decision-making.

---

## Tools & Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## Project Output

 Data Preprocessing
 
 K-Means Clustering Model
 
 Elbow Method Analysis
 
 Cluster Visualization
 
 Customer Segments with Insights
