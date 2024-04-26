# K-means and PCA From Scratch Implementation

## Overview

This repository contains Python implementations of K-means clustering and Principal Component Analysis (PCA) from scratch. These fundamental machine learning algorithms are widely used for clustering and dimensionality reduction tasks, respectively. By implementing them from scratch, you can gain a deeper understanding of their inner workings and improve your proficiency in machine learning concepts.

## Algorithms Implemented

### 1. K-means Clustering

K-means is a popular clustering algorithm used for partitioning data into K clusters based on similarity. The implementation provided in this repository follows the traditional K-means algorithm, including the initialization of centroids, assignment of data points to clusters, and update of centroids until convergence.

### 2. Principal Component Analysis (PCA)

PCA is a technique for reducing the dimensionality of data while preserving its variance. The PCA implementation in this repository computes the principal components of the data matrix, allowing for dimensionality reduction and visualization of high-dimensional data.

## Example Usage

```python
# Example usage of K-means clustering
from k_means import KMeans

# Instantiate KMeans class
kmeans = KMeans(n_clusters=3)

# Fit the model to data
kmeans.fit(X)

# Get cluster centroids
centroids = kmeans.centroids

# Get cluster assignments for data points
labels = kmeans.labels
```
```
# Example usage of Principal Component Analysis (PCA)
from pca import PCA

# Instantiate PCA class
pca = PCA(n_components=2)

# Fit the model to data
pca.fit(X)

# Transform data to reduced dimensionality
X_reduced = pca.transform(X)
```
