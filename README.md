# Density-Based Spatial Clustering of Applications with Noise (DBSCAN)

Advantages : 

- Deals well with clusters of different shapes and sizes, containing noise and outliers.

- Logic : connectivity and reachability


- In tuning : no need to specify the number of clusters to use the algorithm. Just a function to calculate the distance between values and some guidance for what amount of distance is considered “close”." 


Parameters:

- minPts: minimum number of points (a threshold) clustered together for a region to be considered dense.
Rule of thumb : Dimension + 1 (so, min of 3)

- eps (ε): A distance measure that will be used to locate the points in the neighborhood of any point.

### Info:
https://www.kdnuggets.com/2020/04/dbscan-clustering-algorithm-machine-learning.html
