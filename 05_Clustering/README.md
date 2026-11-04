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

