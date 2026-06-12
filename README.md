# Customer Segmentation using K-Means Clustering

## Project Overview

This project implements the K-Means Clustering algorithm to segment retail store customers based on their purchasing behavior. Customer segmentation helps businesses identify groups of customers with similar characteristics, enabling targeted marketing strategies and improved customer relationship management.

## Dataset

The project uses the Mall Customers Dataset, which contains customer demographic information and spending behavior.

### Features Used

* Annual Income (k$)
* Spending Score (1-100)

These features were selected to identify meaningful customer groups based on purchasing patterns and income levels.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Google Colab

## Methodology

### 1. Data Preprocessing

* Loaded and inspected the dataset.
* Checked for missing values.
* Selected relevant features for clustering.
* Standardized the data using StandardScaler.

### 2. Optimal Cluster Selection

The Elbow Method was applied to determine the optimal number of clusters by analyzing the Within-Cluster Sum of Squares (WCSS).

### 3. K-Means Clustering

The K-Means algorithm was trained using the optimal number of clusters to group customers with similar spending behavior and income levels.

### 4. Visualization

Customer segments were visualized using scatter plots to understand cluster distribution and separation.

## Model Evaluation

Since clustering is an unsupervised learning technique, traditional metrics such as accuracy are not applicable.

The model was evaluated using:

### Silhouette Score

* **Silhouette Score:** 0.5547

A Silhouette Score above 0.5 indicates good cluster separation and cohesion, suggesting that the identified customer groups are meaningful and well-defined.

### Inertia (WCSS)

* **Inertia:** 65.5684

Inertia measures how compact the clusters are. Lower values indicate that customers within the same cluster are more similar to each other.

## Results

The K-Means algorithm successfully segmented customers into distinct groups based on annual income and spending score. The clustering results reveal clear customer patterns that can be leveraged for personalized marketing, customer retention strategies, and business decision-making.

## Business Applications

* Targeted Marketing Campaigns
* Customer Retention Programs
* Product Recommendation Systems
* Loyalty Program Design
* Revenue Optimization

## Conclusion

A K-Means Clustering model was successfully developed to segment retail customers based on income and spending behavior. The model achieved a Silhouette Score of 0.5547, indicating good cluster quality and meaningful customer segmentation. The identified customer groups provide valuable insights that can help businesses make data-driven marketing and customer engagement decisions.

## Author

**Vansh**
B.Tech Computer Science & Engineering (AI & ML)
