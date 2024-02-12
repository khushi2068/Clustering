
# Clustering Analysis on Heart Failure Clinical Records

This project demonstrates the application of clustering techniques, specifically KMeans, Spectral Clustering and Hierarchical Clustering (HClust), on the Heart Failure Clinical Records dataset. The goal is to explore the dataset's inherent groupings to uncover patterns related to heart failure clinical records.

## Getting Started

### Prerequisites

Before running the analysis, ensure you have installed the required Python packages:

  ```bash
  pip install ucimlrepo pycaret
  pip install matplotlib scikit-learn pandas numpy
  ```
## Clustering Techniques

### KMeans Clustering

KMeans is a partitioning method that divides the dataset into `k` clusters. It starts with random centroid initialization and iteratively assigns each data point to the nearest cluster while updating the centroids.
