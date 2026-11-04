# Clustering – Spotify Songs

## Project Overview

This project explores unsupervised machine learning techniques to group Spotify songs based on their similarities.

The analysis was developed as part of Artificial Intelligence coursework at the Faculty of Organizational Sciences, University of Belgrade.

## K-Means Clustering

The goal is to identify groups of similar songs using the K-Means clustering algorithm.

### Methodology

1. Data loading and exploration
2. Missing-value analysis and preprocessing
3. Feature selection and correlation analysis
4. Outlier detection and treatment
5. Feature scaling
6. Determining the number of clusters using the Elbow Method
7. Applying K-Means with K = 2 and K = 4
8. Visualizing and interpreting the resulting clusters

### Results

The dataset contains 952 songs.

**K = 2**

- Cluster 1: 402 songs
- Cluster 2: 550 songs

**K = 4**

- Cluster 1: 173 songs
- Cluster 2: 245 songs
- Cluster 3: 229 songs
- Cluster 4: 305 songs

Both solutions were examined to compare how songs are grouped based on their selected characteristics.

## Technologies

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook.

## How to Run

1. Download `KMeans_Clustering.ipynb` and `spotify.csv`.
2. Place both files in the same working directory.
3. Open the notebook in Jupyter Notebook or Google Colab.
4. Run all cells sequentially.

## Hierarchical Clustering

This project uses agglomerative hierarchical clustering to group Spotify songs based on their musical characteristics and chart performance.

### Methodology

1. Data loading and filtering
2. Missing-value handling
3. Feature selection and correlation analysis
4. Outlier detection and treatment
5. Feature normalization using MinMaxScaler
6. Dendrogram analysis using different linkage methods
7. Hierarchical clustering with K = 2 and K = 4
8. Cluster visualization and interpretation

### Results

The analysis was performed on 952 songs using Ward linkage and Euclidean distance.

Two clustering solutions were explored to examine how songs can be grouped based on their similarities.

The resulting clusters were compared using boxplots, cluster sizes, and feature distributions.

### Conclusion

Hierarchical clustering identified groups of songs with similar characteristics without using predefined class labels.

Dendrograms provided a visual representation of the relationships between songs and helped explore different clustering solutions.

### Technologies

Python, Pandas, NumPy, Matplotlib, Seaborn, SciPy, Scikit-learn, Jupyter Notebook.
