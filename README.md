This project focuses on clustering time series data using Dynamic Time Warping (DTW) and hierarchical clustering techniques. 
The goal is to identify meaningful patterns in time series data by applying different clustering methods and comparing their effectiveness.
Initially, K-Means with DTW was used, which suggested three clusters. However, 
further analysis showed one misclustered group, leading to an additional sub-splitting step to refine the results. 
To improve clustering accuracy, Agglomerative Clustering was applied, leveraging dendrogram analysis to determine the optimal number of clusters. 
The hierarchical approach provided a more structured clustering process, and the final model identified four well-separated clusters.
This project demonstrates the advantages of DTW-based clustering for time series data and highlights the importance of choosing the right clustering method for accurate segmentation.
