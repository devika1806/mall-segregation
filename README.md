# Mall Customers Segmentation using K-means Clustering
This project aims to segment customers of a mall based on their spending patterns. K-means clustering is used to group customers into distinct segments based on the products they bought.
# Dataset
This dataset is taken form Kagle
[Dataset](/code/data.csv)
# Kmeans Clustering
K-means clustering is an unsupervised machine learning algorithm that groups data points into a specified number of clusters (k clusters). In this project, k-means clustering was used to segment the Mall customer data into groups based on their purchase behavior and characteristics.

The first thing I did was to determined the optimal number of clusters (k) to use. Then used elbow method to determine the value of  k. The elbow point in the graph indicated that k=5 clusters was optimal.

I then performed k-means clustering with k=5. The algorithm grouped the customers into % clusters based on minimizing the distance between customers within a cluster and maximizing the distance between clusters.

Each cluster was then analyzed  to understand the characteristics and behaviors of the customers in that segment. I looked at metrics like gender, income, spending, offer completion rates, and more.

This analysis revealed that the 5 clusters represented different types of customers with distinct preferences and purchase patterns. Hence,I then proposed targeted offers tailored to each cluster to try to increase customer engagement and revenue.

![Clustering final output](/code/image.png)

In summary, k-means clustering allowed the authors to segment the Starbucks customer data into meaningful groups that provided insights to create more personalized marketing offers. The algorithm grouped customers with similar characteristics and behaviors, which is the goal of customer segmentation.
