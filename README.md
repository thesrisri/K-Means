# K-Means
just a sample program of k-means for understanding purpose
K Means Clustering is an unsupervised machine learning algorithm which
basically means we will just have input, not the corresponding output label. In this
article, we will see its implementation using python.
K Means Clustering tries to cluster your data into clusters based on their similarity. In
this algorithm, we have to specify the number of clusters (which is a hyperparameter) we
want the data to be grouped into.
The K Means Algorithm is:
  • Choose a number of clusters “K”
  • Randomly assign each point to Cluster
  • Until cluster stop changing, repeat the following
      1. For each cluster, compute the centroid of the cluster by taking the mean vector of
          the points in the cluster.
      2. Assign each data point to the cluster for which the centroid is closest
      
  ""  this pyhton code just clusters the data around the centroids and plot them on the graph ""
  ""  a basic program for beginners understanding  """
