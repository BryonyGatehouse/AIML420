# Assignment 1, Part 1 : Nearest Neighbour

Create a program which implements the nearest neighbour method. This should work with any number of k (closest neighbours).

The Advantages of the K-Nearest Neighbour method is:
- Lack of training period
- Easy Implementation
- Accepts new data (without re-training)
- Can learn non-linear decision boundaries
- Choice of distance formula
The Disadvantages of the K-Nearest Neighbour method is:
- Compares each instance
- Sensitive to missing data
- Assumes equal imporatance to all features

To edit the program to use K-Fold Cross Validation Method:
- Combine the test and training data in one set
- Split the set evenly into k sub files
- Iterate through each file such that:
  - That file is the test set
  - The others combine to be the training set

To group without class labels (using the K-Means Cluster Method):
- From the training data, choose k random instances to be the centroids
- For each centroid, create a list to hold their cluster
- For each instance, place in the closest centroid's cluster
  - Replace the centroid with the mean of each cluster (the mean of each feature)
  - Repeat until the changes fall below a threshold

Create a program with implements the K-Means Clustering method. Comparing the results from the K-Nearest Neighbour Classifier proved that it produced almost identical groupings. 
