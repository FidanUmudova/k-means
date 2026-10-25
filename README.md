# K-Means Clustering Implementation from Scratch

This repository contains the core function implementations for the **K-Means Clustering** algorithm, developed using Python and NumPy as part of a Machine Learning coursework assignment.

##  Implemented Functions

1. **`find_closest_centroids` (Cluster Assignment Phase):**
   - Computes the squared L2-norm (distance) between each training example $x^{(i)}$ and all cluster centroids $\mu_j$.
   - Assigns every training example to its closest centroid, returning a one-dimensional array of indices ranging from $0$ to $K-1$.

2. **`compute_centroids` (Centroid Mean Computation Phase):**
   - Recalculates the position of each centroid by computing the mean of all data points assigned to that specific cluster.

