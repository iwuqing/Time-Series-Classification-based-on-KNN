# SmoothSubspace dataset

The data was originally intended for testing whether a clustering algorithm is able to extract smooth subspaces for clustering time series data [1]. 

There are 3 classes corresponding to which cluster the time series belong to. Each time series contain a continuous subspace spanning over 5 continuous time stamps. 
- For cluster 1, it is from time stamp 1-5 
- For cluster 2, it is from time stamp 6-10
- For cluster 3, it is from time stamp 11-15. 

The rest of the time series are randomly generated.

Train size: 150

Test size: 150

Missing value: No

Number of classses: 3

Time series length: 15

There is nothing to infer from the order of examples in the train and test set.

Data created by Xiaohui Huang et al. (see [1]). Data edited by Hoang Anh Dau.

[1] Huang, Xiaohui, et al. "Time series k-means: A new k-means type smooth subspace clustering for time series data." Information Sciences 367 (2016): 1-13.