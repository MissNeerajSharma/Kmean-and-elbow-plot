# Kmean-and-elbow-plot

Clustering With K Means - Python Tutorial

K Means Clustering is unsupervised-learning technique and very simple method of grouping individual data points into clusters. Goal of the technique is to group points into clusters. Each group is associated with its centre of mass. Challenge is to identify the group and centres of the mass (K-centroid). Each of data points is governed by distance from the centres of the cluster. Initially unclassified data can be classified into categories.

K-Means Pseudocode
## K-Means Clustering 
1. Choose the number of clusters(K) and obtain the data points 
2. Place the centroids c_1, c_2, ..... c_k randomly 
3. Repeat steps 4 and 5 until convergence or until the end of a fixed number of iterations
4. for each data point x_i:
       - find the nearest centroid(c_1, c_2 .. c_k) 
       - assign the point to that cluster 
5. for each cluster j = 1..k
       - new centroid = mean of all points assigned to that cluster
6. End 
  Source: https://towardsdatascience.com/k-means-clustering-introduction-to-machine-learning-algorithms-c96bf0d5d57a


![alt text](https://github.com/MissNeerajSharma/Kmean-and-elbow-plot/blob/master/0_f9HcysjkU6XyM1hb.gif)
