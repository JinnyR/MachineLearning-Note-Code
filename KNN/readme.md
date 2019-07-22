######

## KNN: k-Nearest Neighbor 



1. a non-parametric method used for classification and regression.
2. TODO



#### KNN VS. K-Means



| KNN                                                          | K-Means                                                      |
| :----------------------------------------------------------- | :----------------------------------------------------------- |
| It is a **Supervised** learning technique                    | It is an **Unsupervised** learning technique                 |
| It is used mostly for **Classification**, and sometimes even for **Regression** | It is used for **Clustering**                                |
| ‘K’ in KNN is the number of nearest neighbours used to classify or (predict in case of continuous variable/regression) a test sample | ‘K’ in K-Means is the number of clusters the algorithm is trying to identify/learn from the data. The clusters are often unknown since this is used with Unsupervised learning. |
| It is used for classification and regression of known data where usually the target attribute/variable is known before hand. | It is typically used for scenarios like understanding the population demomgraphics, market segmentation, social media trends, anomaly detection, etc. where the clusters are unknown to begin with. |
| K-NN doesn’t have a training phase as such. But the prediction of a test observation is done based on the K-Nearest (often euclidean distance) Neighbours (observations) based on weighted averages/votes._______________________________________ | In training phase of K-Means, K observations are arbitrarily selected (known as centroids). Each point in the vector space is assigned to a cluster represented by nearest (euclidean distance) centroid. Once the clusters are formed, for each cluster the centroid is updated to the mean of all cluster members. And the cluster formation restarts with new centroids. This repeats until the centroids themselves become mean of clusters, i.e., when updating centroids to mean doesn’t change them. The prediction of a test observation is done based on nearest centroid. |

from: http://abhijitannaldas.com/ml/kmeans-vs-knn-in-machine-learning.html

CODE:

- 

