# Clustering-using-k-means

**Introduction:**
In this project, I will analyze a dataset of mall customers' behavior and preferences to identify different customer segments based on their annual income and spending score using the K-means algorithm. The aim is to aid mall management in understanding their customers' preferences better and improve services accordingly.

**Dataset:**
The dataset used in this project can be found on https://www.kaggle.com/datasets/shwetabh123/mall-customers. The dataset contains 200 rows and 5 columns. The columns include CustomerID, Gender, Age, Annual Income (k$), and Spending Score (1-100).

**Objective:**
My objective is to cluster customers based on their annual income and spending score to identify different customer segments.

**Methodology:**
I employed the following methodology:
1. Data exploration: I explored the dataset by displaying its shape, additional information about the data types of each column, and the first 5 rows of the data. Additionally, a summary of statistics was generated using the data.describe() method.
2. Data Visualization and Preprocessing: Histograms of continuous variables were created to visualize data distribution and understand the underlying characteristics of the data. Furthermore, feature scaling was conducted using MinMaxScaler.
3. Model Implementation: Two different methods were employed to ascertain the optimal number of clusters - the elbow method and the silhouette method. Afterward, the K-means algorithm with 3, 4, and 5 clusters was implemented to segment the customers based on their annual income and spending score.
4. Model Evaluation: Within-Cluster Sum of Squares (WCSS) was used to evaluate the quality of our 3 clustering models with different numbers of clusters.

**Steps:**
1. Imported necessary libraries
2. Loaded the "Mall_Customers.csv" dataset
3. Explored the dataset
4. Visualized data distribution and performed feature scaling
5. Ascertained the optimal number of clusters using the elbow method and the silhouette method
6. Implemented the K-means algorithm with 3, 4, and 5 clusters
7. Evaluated the quality of our clustering models using WCSS
