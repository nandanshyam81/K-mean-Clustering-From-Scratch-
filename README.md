* K-Means Clustering from scratch *

*Clustering* </br>
Clustering is basically a type of unsupervised learning method, which groups the unlabelled dataset. It can be defined as "A way of grouping the data points into different clusters, consisting of similar data points.The objects with the possible similarities remain in a group that has less or no similarities with another group.

> *K-Means Clustering* </br>
K-Means clustering is an unsupervised learning algorithm which groups the unlabeled dataset into different clusters.Here K defines the number of pre-defined clusters that need to be created in the process, as if k=2, there would be two clusters.

![image](https://user-images.githubusercontent.com/109072424/207693933-3ec0c9e3-6298-4100-9b5c-2005894c00e9.png)


> We are given a data set of items, with certain features, and values for these features (like a vector).The task is to categorize those items into groups.
> STEP-1 : First, we need to choose the number of clusters (k)
> STEP-2 : We need to select k random points from the data as centroids.
> STEP-3 : Then, we need to assign all the points to the closest cluster centroid.
> STEP-4 : Then, we need to recompute the centroid for the newly formed clusters.
> STEP-5 : Repeat step-3 and step-4

* Stopping criteria for K-Means *
There are esentially three stopping criteria that can be adopted to stop k means clustering algorithm:
> Centroids of newly formed clusters do not change.
> Points remain in the same cluster.
> Maximum number of iterations are reached.



