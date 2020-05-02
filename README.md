# Clustering-

It is an unsupervised learning algorithm which makes clusters based on common characteristics. It only depends on independent features.
There is no target variable. There are a metrics for the same , namely:

a. Inertia : Within cluster sum of square distances. Ideally inertia should be lower.

b. Silhouette : Measures how dense and seperated the clusters are. Silhouette coeffecient is always between -1 and 1. 
Must always be to the positive side.

Important points:

a) The KMeans algorithm is a greedy algorithm and will always look for convergance faster. 

b) It will always tend to reduce inertia. 

c) Clusters can be of various shapes. 

The most important hyperparameter of the KMeans algorithm is the number of clusters. Choosing the optimal number of clusters is 
always the catch.

Choosing number of clusters based on Inertia:

![cluster4](https://user-images.githubusercontent.com/55191934/80860969-13463d80-8c89-11ea-87c3-2c7fb928728d.PNG)

Choosing number of clusters based on Silhouette:

![cluster5](https://user-images.githubusercontent.com/55191934/80860990-38d34700-8c89-11ea-8098-95a08aeea744.PNG)

Many times the clusters formed can be elongated and KMeans will always look to reduce inertia instead of classifying correctly.

Elongated clusters:

![cluster1](https://user-images.githubusercontent.com/55191934/80861014-69b37c00-8c89-11ea-83fe-6566f75d5437.PNG)

![cluster2](https://user-images.githubusercontent.com/55191934/80861025-79cb5b80-8c89-11ea-9a19-562e1ba2905b.PNG)


The Gaussian Mixture Model (GMM) fixes this problem as it tends to correctly classify the clusters.

![cluster3](https://user-images.githubusercontent.com/55191934/80861042-9e273800-8c89-11ea-82fa-07ab9e7afdd4.PNG)


Choosing the optimal number of components using GMM:

![cluster6](https://user-images.githubusercontent.com/55191934/80861064-d0389a00-8c89-11ea-943a-16835373ae2c.PNG)


Final results:

![cluster7](https://user-images.githubusercontent.com/55191934/80861080-e6def100-8c89-11ea-82d2-e23cdef5e58d.PNG)

