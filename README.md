# K Means Clustering with Python and Scikit-Learn

K-Means clustering is one of the most popular unsupervised machine learning algorithm. It is used to find homogeneous groups in the data that display the same behaviour. In this project, I implement K-Means clustering with Python and Scikit-Learn.

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


===============================================================================

## 2. The goals of clustering


The goal of clustering algorithm is to determine the intrinsic grouping in a set of unlabelled data. So, K-Means clustering is used 
to find homogeneous groups in the data that display the same behaviour. The number of groups is represented by the variable K. The algorithm works iteratively to assign each data point to one of K groups. Data points are grouped based on their similar characteristics.


===============================================================================


## 3. K-Means clustering intuition


===============================================================================


## 4. Choosing the value of k


The K-Means algorithm depends upon finding the number of clusters and data labels for a pre-defined value of K. To find the number of clusters in the data, we need to run the K-Means clustering algorithm for different values of K and compare the results. So, the performance of K-Means algorithm depends upon the value of K. We should choose the optimal value of K that gives us best performance. There are different techniques available to find the optimal value of K. The most common technique is the **elbow method** which is described below.


===============================================================================


## 5. The elbow method


===============================================================================


## 6. Advantages and disadvantages of K-Means


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


===============================================================================

## 8. Results and conclusion


===============================================================================

## 9. Applications of K-Means 


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


