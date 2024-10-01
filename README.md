# PRODIGY_ML_02
Customer Segmentation using K-means Clustering
Project Overview
This project implements the K-means clustering algorithm to segment customers based on their annual income and spending score. By clustering customers, we can better understand different purchasing behaviors and create targeted marketing strategies.

The code displays basic information about the DataFrame, including the number of entries and data types.
It checks for missing values, confirming there are none.
The 'Gender' column is converted to a numerical format (0 for Male, 1 for Female).
The 'CustomerID' column is dropped since it's not needed for clustering.
Descriptive statistics for the remaining columns are generated.
Means is applied with 2 clusters. A warning related to potential memory issues on Windows is noted.
The resulting cluster labels are added to a copy of the DataFrame.

A 3D scatter plot visualizing the clusters based on 'Spending Score', 'Annual Income', and 'Age' is created and saved as an image.
The clustering process is repeated for 8 clusters, again analyzing and visualizing the results.

Summary:
The code effectively segments customers into different groups based on their demographics and spending behavior using KMeans clustering, providing insights into each segment's characteristics. The use of visualizations aids in understanding the clustering results.



