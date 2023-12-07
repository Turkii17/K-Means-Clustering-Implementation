# K-Means-Clustering-Implementation


K-Means Clustering Implementation

This repository contains a Python implementation of the K-Means clustering algorithm using popular libraries such as NumPy, Pandas, Matplotlib, and Seaborn. The code provides a clear and concise way to perform K-Means clustering on a given dataset.

# Features:
Initialization of Random Centroids:

The init_random function initializes K random centroids from the input dataset.
Finding Closest Centroids:

The find_closest_centroids function assigns each data point to the nearest centroid based on Euclidean distance.
Computing Centroids:

The compute_centroids function updates the centroids based on the mean of data points assigned to each cluster.
Running K-Means:

The run_kMeans function executes the K-Means algorithm, updating centroids iteratively and visualizing the clustering process.

# Usage:
Generate Synthetic Dataset:

The code includes an example of generating a synthetic dataset using create_dataset_sklearn.py.
Set Parameters:

Adjust the number of clusters (K) and maximum iterations in the run_kMeans function according to your requirements.
Run the Code:

Execute the provided example to see K-Means clustering in action on the generated dataset.


#Visualization:
The code includes visualizations at each iteration, showing the data points colored by their assigned clusters and the centroids updated in each step.

Feel free to use and modify this code for your clustering tasks. If you find any issues or have suggestions for improvement, please create an issue or submit a pull request.

Happy Clustering!
