# Clustering Geolocation Data Intelligently in Python

We have taxi rank locations, and want to define key clusters of these taxis where we can build service stations for all taxis operating in that region.

## Prerequisites

- Basic Matplotlib skills for plotting 2-D data clearly.
- Basic understanding of Pandas and how to use it for data manipulation.
- The concepts behind clustering algorithms.

## Project Outline
1. Exploratory Data Analysis
2. Visualizing Geographical Data
3. Clustering Strength / Performance Metric
4. K-Means Clustering

<img src="images/kmeans.JPG" alt="drawing" width="800" height="600"/>

![output](https://github.com/sudip-padhye/Clustering-Geolocation-Data-Intelligently-using-HDBSCAN/blob/master/kmeans_70.html "k-means output")

5. DBSCAN
6. HDBSCAN
7. Addressing Outliers

<img src="images/hybrid.JPG" alt="drawing" width="800" height="600"/>

![output](https://github.com/sudip-padhye/Clustering-Geolocation-Data-Intelligently-using-HDBSCAN/blob/master/hybrid.html "hybrid output")

## Further Reading

For some additional reading, feel free to check out [K-Means](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html), [DBSCAN] (https://scikit-learn.org/stable/modules/generated/sklearn.cluster.DBSCAN.html), and [HDBSCAN] (https://hdbscan.readthedocs.io/en/latest/) clustering respectively.

It may be of use to also check out [other forms of clustering] (https://scikit-learn.org/stable/modules/clustering.html) that are commonly used and available in the scikit-learn library. HDBSCAN documentation also includes [a good methodology] (https://hdbscan.readthedocs.io/en/latest/comparing_clustering_algorithms.html) for choosing your clustering algorithm based on your dataset and other limiting factors.