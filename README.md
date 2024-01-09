# Hierarchial-Cluster

This repository contains Python scripts for performing hierarchical clustering on a dataset and visualizing the results using a dendrogram and a 2D scatter plot via PCA reduction. The primary goal is to identify distinct groups within the data that may correspond to different categories of interest, such as risk levels in a medical dataset.

Description of the Analysis

The script follows these steps:

Data Loading: Reads the dataset from a CSV file.
Preprocessing: Drops categorical columns and standardizes the numerical data.
PCA Dimensionality Reduction: Reduces the data to two principal components for visualization purposes.
Hierarchical Clustering: Applies agglomerative hierarchical clustering to the reduced data and plots a dendrogram.
Cluster Identification: Based on the dendrogram, determines the number of clusters.
Cluster Validation: Computes the silhouette score to evaluate clustering quality.
Cluster Visualization: Visualizes the clusters on a 2D scatter plot using PCA-reduced data.

Output

After running the script, you will see two plots:

A dendrogram representing the hierarchical clustering.
A 2D scatter plot showing the data points colored according to the cluster they belong to, reduced to two principal components.
