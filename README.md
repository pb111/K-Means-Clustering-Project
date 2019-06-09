# K-Means Clustering with Python and Scikit-Learn


K-Means clustering is one of the most popular unsupervised machine learning algorithm. K-Means clustering is used to find intrinsic groups within the unlabelled dataset and draw inferences from them. In this project, I implement K-Means clustering with Python and Scikit-Learn. I have used `Facebook Live Sellers in Thailand` dataset for this project. I implement K-Means clustering to find intrinsic groups within this dataset that display the same `status_type` behaviour. The `status_type` behaviour variable consists of posts of a different nature (video, photos, statuses and links).

===============================================================================

## Table of Contents

1.	Introduction to K-Means clustering
2.	The goals of clustering
3.	K-Means clustering intuition
4.	Choosing the value of k
5.	The elbow method
6.	Advantages and disadvantages of K-Means
7.	The problem statement
8.	Results and conclusion
9.	Applications of K-Means 
10.	References


===============================================================================


## 1. Introduction to K-Means clustering

Machine learning algorithms can be broadly classified into two categories - supervised and unsupervised learning. There are other categories also like semi-supervised learning and reinforcement learning. But, most of the algorithms are classified as supervised or unsupervised learning. The difference between them happens because of presence of target variable. In unsupervised learning, there is 
no target variable. The dataset only has input variables which describe the data. This is called unsupervised learning.


K-Means clustering is the most popular unsupervised learning algorithm. It is used when we have unlabelled data which is data without defined categories or groups. The algorithm follows an easy or simple way to classify a given data set through a certain number of clusters, fixed apriori. K-Means algorithm works iteratively to assign each data point to one of K groups based on the features that 
are provided. Data points are clustered based on feature similarity.

K-Means clustering can be represented diagrammatically as follows:-


![K-Means](https://github.com/pb111/K-Means-Clustering-Project/blob/master/Images/K-Means.png)


===============================================================================

## 2. The goals of clustering


The goal of clustering algorithm is to determine the intrinsic grouping in a set of unlabelled data. So, K-Means clustering is used 
to find homogeneous groups in the data that display the same behaviour. The number of groups is represented by the variable K. The algorithm works iteratively to assign each data point to one of K groups. Data points are grouped based on their similar characteristics.


===============================================================================


## 3. K-Means clustering intuition


K-Means clustering is used to find intrinsic groups within the unlabelled dataset and draw inferences from them. It is based on centroid-based clustering.


**Centroid** - A centroid is a data point at the centre of a cluster. In centroid-based clustering, clusters are represented by a centroid. It is an iterative algorithm in which the notion of similarity is derived by how close a data point is to the centroid of the cluster.


K-Means clustering works as follows:-

The K-Means clustering algorithm uses an iterative procedure to deliver a final result. The algorithm requires number of clusters K and the data set as input. The data set is a collection of features for each data point. The algorithm starts with initial estimates for the K centroids. The algorithm then iterates between two steps:-


### 1. Data assignment step

Each centroid defines one of the clusters. In this step, each data point is assigned to its nearest centroid, which is based on the squared Euclidean distance. So, if ci is the collection of centroids in set C, then each data point is assigned to a cluster based on minimum Euclidean distance. 


### 2. Centroid update step


In this step, the centroids are recomputed and updated. This is done by taking the mean of all data points assigned to that centroid’s cluster. 


The algorithm then iterates between step 1 and step 2 until a stopping criteria is met. Stopping criteria means no data points change the clusters, the sum of the distances is minimized or some maximum number of iterations is reached.

This algorithm is guaranteed to converge to a result. The result may be a local optimum meaning that assessing more than one run of the algorithm with randomized starting centroids may give a better outcome.


The K-Means intuition can be represented with the help of following diagram:-


![K-Means clustering example](https://github.com/pb111/K-Means-Clustering-Project/blob/master/Images/K-Means%20clustering%20example.jpg)

===============================================================================


## 4. Choosing the value of k


The K-Means algorithm depends upon finding the number of clusters and data labels for a pre-defined value of K. To find the number of clusters in the data, we need to run the K-Means clustering algorithm for different values of K and compare the results. So, the performance of K-Means algorithm depends upon the value of K. We should choose the optimal value of K that gives us best performance. There are different techniques available to find the optimal value of K. The most common technique is the **elbow method** which is described below.


===============================================================================


## 5. The elbow method


The elbow method is used to determine the optimal number of clusters in k-means clustering. The elbow method plots the value of the cost function produced by different values of k. The below diagram shows how the elbow method works:-


![Elbow method in K-Means](https://github.com/pb111/K-Means-Clustering-Project/blob/master/Images/Elbow%20method%20in%20K-Means.png)


We can see that, if k increases, average distortion will decrease.  Then each cluster will have fewer constituent instances, and the instances will be closer to their respective centroids. However, the improvements in average distortion will decline as k increases. 
The value of k at which improvement in distortion declines the most is called the elbow, at which we should stop dividing the data into further clusters.

===============================================================================


## 6. Advantages and disadvantages of K-Means algorithm


The advantages of K-Means are as follows:-

1.	K-Means is a fast, robust and easier to understand.
2.	K-Means is a relatively efficient clustering algorithm that helps to find intrinsic groups within the unlabelled dataset.
3.	K-Means give best result when data set are distinct and well separated from each other.


Disadvantages of K-Means are listed below:-

1.	The learning algorithm requires apriori specification of the number of cluster centres. 
2.	If there are two highly overlapping data, then K-Means will not be able to detect that there are two clusters.
3.	The K-Means algorithm is not invariant to non-linear transformations. It fails for non-linear dataset.
4.	The algorithm is unable to handle noisy data and outliers.
5.	K-Means algorithm is applicable only when mean is defined. So, it fails for categorical data. 


===============================================================================

## 7. The problem statement

In this project, I implement K-Means clustering with Python and Scikit-Learn. K-Means clustering is used to find intrinsic groups 
within the unlabelled dataset and draw inferences from them. I have used `Facebook Live Sellers in Thailand` dataset for this project, downloaded from the UCI Machine Learning repository. The dataset can be found at the following url-

https://archive.ics.uci.edu/ml/datasets/Facebook+Live+Sellers+in+Thailand

The dataset consists of Facebook pages of 10 Thai fashion and cosmetics retail sellers. The `status_type` behaviour variable consists of posts of a different nature (video, photos, statuses and links). It also contains engagement metrics of comments, shares and reactions. I implement K-Means clustering to find intrinsic groups within this dataset that display the same `status_type` behaviour. 


===============================================================================

## 8. Results and conclusion


i

===============================================================================

## 9. Applications of K-Means Clustering


K-Means clustering is the most common unsupervised machine learning algorithm. It is widely used for many applications which include-

1.	Image segmentation
2.	Customer segmentation
3.	Species clustering
4.	Anomaly detection
5.	Clustering languages


===============================================================================


## 10. References

The work done in this project is inspired from following books and websites:-

1.	Udemy course – Machine Learning – A Z by Kirill Eremenko and Hadelin de Ponteves

2.	https://en.wikipedia.org/wiki/K-means_clustering

3.	https://jakevdp.github.io/PythonDataScienceHandbook/05.11-k-means.html

4.	https://www.datacamp.com/community/tutorials/k-means-clustering-python

5.	https://www.datascience.com/blog/k-means-clustering

6.	https://acadgild.com/blog/k-means-clustering-algorithm


