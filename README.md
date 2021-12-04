# Determining-clusters
Determine optimum number of clusters in python 
We will be conducting Clustering analysis on the given dataset 'illness study' how to choose the optimal numbers of clusters.

The “Elbow” Method
Probably the most well-known method, the elbow method, in which the sum of squares at each number of clusters is calculated and graphed, and the user looks for a change of slope from steep to shallow (an elbow) to determine the optimal number of clusters. This method is inexact, but still potentially helpful.
As you can see it shows the range but not exactly how many numbers of clusters to be specific.

The Silhouette Method
Another visualization that can help determine the optimal number of clusters is called the silhouette method. Average silhouette method computes the average silhouette of observations for different values of k. The optimal number of clusters k is the one that maximize the average silhouette over a range of possible values for k, it's also show how far the datapoints are within the cluster and how far the datapoints in the cluster can be measure by one method to give a 
clear score, the maximum score can be reach by silhouette method, we can use both method, but silhouette method give you a sure score whereas in Elbow method it gives you range.
Silhouette methob also suggests an optimal of 2 clusters.
