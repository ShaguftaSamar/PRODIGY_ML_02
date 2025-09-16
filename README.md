# Task-02

Create a K-means clustering algorithm to group customers of a retail store based on their purchase history.

This project focuses on performing customer segmentation using the K-Means clustering algorithm. The goal is to group customers of a retail store based on their purchasing behavior and spending patterns. Understanding these clusters helps businesses target the right customers, optimize marketing strategies, and improve overall engagement.

## Dataset

**Source:** [https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)


**Dataset Attributes:**

* CustomerID: Unique ID for each customer
* Gender: Male or Female
* Age: Customer's age
* Annual Income (k\$): Income in thousand dollars
* Spending Score (1-100): Score based on purchasing behavior


**Features used for clustering:**

* Annual Income (k\$)
* Spending Score (1-100)


## Objective

* Segment customers into meaningful groups based on income and spending behavior
* Identify patterns to support marketing campaigns and customer engagement strategies


## Steps Performed

1. **Import Libraries:** NumPy, Pandas, Matplotlib, Seaborn, scikit-learn (for clustering and evaluation)
2. **Load Dataset & Data Quality Check:** Checked for missing values, duplicates, and explored basic statistics
3. **Exploratory Data Analysis (EDA):** Visualized Gender, Age, Annual Income, and Spending Score distributions
4. **Feature Selection & Scaling:** Selected relevant features and normalized data using StandardScaler
5. **Optimal Cluster Selection:** Applied the Elbow Method and Silhouette Scores to determine the optimal number of clusters
6. **K-Means Clustering:** Assigned cluster labels (0–4) to customers based on similarity
7. **Cluster Profiles & Summary:** Analyzed clusters for average income, spending score, and customer count
8. **Data Visualization:** Visualized clusters using scatter plots, boxplots, PCA-reduced 2D plots, and pairplots
9. **Cluster Evaluation Metrics:** Measured Silhouette Score, Calinski-Harabasz Index, and Davies-Bouldin Index for cluster validity


## Key Insights

The K-Means algorithm identified 5 distinct customer clusters based on annual income and spending score.
* Each cluster represents a group of customers with similar income and spending patterns
* The clusters can help the retail store understand different customer behaviors and plan targeted marketing campaigns, promotions, and loyalty programs
* Detailed cluster statistics, including average income, spending score, and customer count, are available in the analysis


## Tools & Libraries

* Python 3.x
* NumPy & Pandas – data handling and analysis
* Matplotlib & Seaborn – visualization
* scikit-learn – K-Means, scaling, PCA, evaluation metrics
