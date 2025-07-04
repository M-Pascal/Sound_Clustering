# **Sound Clustering**

## **Overview**

This repository contains visualizations shows the analysis of unlabeled sound data. 
The visualizations are created using various clustering techniques and dimensionality reduction methods to explore and understand the structure of the sound data.
Below is a description of each visualization included in this repository.

## 1. **Feature Extraction Visualization**

**Description**:

   - This visualization represents the extracted features from the sound data. The features are derived using Mel Spectrograms, which capture the frequency content of the sound signals over time.
   - The plot shows the mean Mel Spectrogram values across different frequency bins, providing insights into the spectral characteristics of the sound data.
     
[![download.png](https://i.postimg.cc/wvPbXbD8/download.png)](https://postimg.cc/gXVDdsMN)

## 2.This visualizations comparing **PCA** and **t-SNE** for dimensionality reduction in 3D space.

- Principal Component Analysis (PCA) is a linear dimensionality reduction technique that projects high-dimensional data into a lower-dimensional space 
while preserving as much variance as possible.

- The PCA visualization shows a more spread-out distribution of points, reflecting its ability to retain global structure Distributed Stochastic Neighbor Embedding (t-SNE) is a non-linear dimensionality reduction method that focuses on preserving local structures. 

- The t-SNE visualization presents clusters that are more compact and highlight relationships between similar data points.

[![download-1.png](https://i.postimg.cc/zB3cR1bF/download-1.png)](https://postimg.cc/qhVL9SGN)

## 3. **Elbow Method Visualization**

**Description**:

   -   This visualization illustrates the Elbow Method used to determine the optimal number of clusters for the K-Means clustering algorithm.
   - The plot shows the inertia (a measure of how internally coherent clusters are) on the y-axis against the number of clusters on the x-axis.
   -  The "elbow" point in the plot indicates the optimal number of clusters, where adding more clusters does not significantly reduce inertia.
   -  This method helps in selecting the most appropriate number of clusters for the sound data.

[![download-3.png](https://i.postimg.cc/pLY7wCMz/download-3.png)](https://postimg.cc/mPk8MQDg)

## 2. **K-Means Clustering Visualization**
**Description**:
   
   -  This visualization represents the results of applying the K-Means clustering algorithm to the sound data.
   -  The plot shows the clusters formed by grouping similar sound features together, with each cluster represented by a different color.
   -   The x-axis and y-axis represent the reduced dimensions of the data, and the plot helps in understanding the distribution and separation of clusters identified by the K-Means algorithm.

[![download-4.png](https://i.postimg.cc/3xHVf6V3/download-4.png)](https://postimg.cc/3dntdL3q)


## 4. **Final Clusters (t-SNE Visualization with K-Means Labels)**

**Description**:
   
   - This visualization displays the final clusters obtained from the K-Means clustering algorithm, visualized in a 2D space using t-SNE (t-Distributed Stochastic Neighbor Embedding).
   -  The plot shows the t-SNE components on the x and y axes, with each point colored according to its K-Means cluster label.
   -  This visualization helps in understanding the separation and distribution of clusters in a reduced-dimensional space, providing insights into the effectiveness of the K-Means clustering.

[![download-5.png](https://i.postimg.cc/R0gYF0F0/download-5.png)](https://postimg.cc/7CT9twSv)
     
