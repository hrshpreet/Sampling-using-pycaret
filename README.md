This repository contains the code for an assignment on clustering techniques applied to the Wholesale Dataset. Different clustering algorithms, preprocessing techniques, and evaluation parameters were explored in this assignment.

## Clustering Techniques:

- **K-Means Clustering:** An unsupervised clustering algorithm aiming to partition data into K clusters.
- **Hierarchical Clustering:** Builds a tree of clusters where each node is a cluster consisting of one or more data points.
- **Mean Shift Clustering:** A non-parametric clustering technique aiming to discover dense regions in data.

## Evaluation Parameters:

- **Silhouette Score:** Measures the quality of clusters.
- **Calinski-Harabasz Index:** Measures cluster separation and compactness.
- **Davies-Bouldin Index:** Evaluates cluster dispersion.

## Preprocessing Techniques:

- **None:** No preprocessing applied.
- **Normalization:** Scaling each feature to a range.
- **PCA (Principal Component Analysis):** Technique for dimensionality reduction.
- **Transform:** Transforming features using specific transformations.
- **PCA + Transform (PCA+T):** Combining PCA with feature transformation.
- **PCA + Transform + Normalization (PCA+T+N):** Combining PCA, feature transformation, and normalization.

## Dataset Details:
- Number of Features: 8
- Number of Rows: 440

## Best Clustering Method:
- **Hierarchical Clustering:** Based on the evaluation metrics and analysis, the hierarchical clustering method yielded the best results.

## Best Number of Clusters:
- **4:** After experimentation and evaluation, the optimal number of clusters identified for the dataset was 4.

## Best Silhouette Score:
- **0.95:** The silhouette score, indicating the quality of clustering, was highest for the hierarchical clustering method with a score of 0.95.
