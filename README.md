Customer Segmentation using K-Means Clustering
This project applies unsupervised machine learning to perform customer segmentation for a retail business. Using the K-Means clustering algorithm, the goal is to identify distinct groups of customers based on their annual income and spending habits. The insights gained from this analysis can be used to develop targeted marketing strategies.

Dataset
The dataset used is the Mall Customer Segmentation Data from Kaggle. It contains customer information including CustomerID, Gender, Age, Annual Income (k$), and Spending Score (1-100).

Project Structure
customer_segmentation.ipynb: A Jupyter Notebook containing all the Python code for data analysis, clustering, and visualization.

Mall_Customers.csv: The dataset used in this project.

kmeans_model.joblib: The trained K-Means model, saved for future use.

Key Steps
Data Loading and Exploration: The dataset is loaded and checked for missing values and a general statistical overview.

Feature Selection: The 'Annual Income (k$)' and 'Spending Score (1-100)' columns are selected for clustering.

Determining Optimal Clusters: The Elbow Method is used to find the optimal number of clusters for the dataset.

K-Means Clustering: The K-Means algorithm is applied to segment the customers into five distinct groups.

Visualization and Interpretation: A scatter plot is generated to visualize the clusters, and each segment is analyzed to understand its unique characteristics.

Results and Marketing Insights
The analysis resulted in five distinct customer segments, each with unique characteristics that a marketing team can leverage:

High Income, Low Spending: Customers with high income who are not frequent spenders at the mall.

Average Income, Average Spending: The largest and most typical customer group.

High Income, High Spending: The most valuable "VIP" customers.

Low Income, High Spending: Customers who are highly responsive to promotions and sales.

Low Income, Low Spending: Customers who are not a primary target for aggressive marketing campaigns.

These insights can be used to create personalized marketing campaigns, optimize pricing, and improve customer experience.

Technologies Used
Python

Pandas for data manipulation

Scikit-learn for the K-Means algorithm

Matplotlib and Seaborn for data visualization

Jupyter Notebook for the analysis environment
