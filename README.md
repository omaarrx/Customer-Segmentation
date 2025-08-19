# Customer-Segmentation
Cluster mall customers by income and spending score. Scale data, apply K-Means with elbow method to find optimal k, and visualize clusters. Bonus: try DBSCAN, compare results, and analyze average spending per segment for business insights.

This task focuses on segmenting customers into groups based on their characteristics, helping businesses understand shopping behavior and tailor strategies. The recommended dataset is the Mall Customer Dataset from Kaggle, which includes details such as Customer ID, Gender, Age, Annual Income, and Spending Score.

The project begins with data preprocessing, including cleaning, handling missing values, and feature scaling to ensure fair comparisons. Initial exploratory data analysis (EDA) through scatter plots and histograms reveals spending and income distributions.

Next, the K-Means clustering algorithm is applied. The Elbow Method (and optionally the Silhouette Score) is used to determine the optimal number of clusters. Customers are then grouped based on Annual Income and Spending Score, and clusters are visualized in 2D scatter plots, with distinct colors representing segments.

To enrich the analysis, you may experiment with additional features such as Age or Gender, applying dimensionality reduction techniques (e.g., PCA) for visualization when needed.

As a bonus extension, the task introduces alternative clustering methods like DBSCAN, which can automatically detect clusters of varying shapes and handle outliers. Finally, cluster profiles are created by analyzing average spending, income, and demographics per group, providing actionable insights into customer behavior for targeted marketing strategies.
