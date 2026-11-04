# k-Nearest Neighbors (kNN) – Spotify Streams Prediction

## Project Overview

This project applies the k-Nearest Neighbors (kNN) classification algorithm to predict whether a Spotify song has a high number of streams.

The analysis was completed as part of Intelligent Systems coursework at the Faculty of Organizational Sciences, University of Belgrade.

## Dataset

The dataset contains information about popular Spotify songs from 2023, including release dates, playlist appearances, chart positions, and musical characteristics.

**Target variable:** `HighStreams`

- `1` – The song has a stream count above the third quartile.
- `0` – The song has a stream count at or below the third quartile.

## Methodology

1. Data loading and exploration
2. Creating the target variable
3. Missing-value analysis and preprocessing
4. Feature selection and visualization
5. Feature scaling using RobustScaler
6. Encoding categorical features
7. Train/test split
8. Hyperparameter tuning using 10-fold cross-validation
9. kNN classification
10. Evaluation using a confusion matrix and classification metrics

## Technologies

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, SciPy and Jupyter Notebook.

## Model Evaluation

The model is evaluated using Accuracy, Precision, Recall and F1-score.

The analysis examines how effectively kNN distinguishes highly streamed songs from other songs.

## How to Run

1. Download `KNN.ipynb` and `spotify.csv`.
2. Place both files in the same working directory.
3. Open the notebook in Jupyter Notebook or Google Colab.
4. Run all cells sequentially.

## Academic Reference

Based on university coursework in Intelligent Systems at the Faculty of Organizational Sciences, University of Belgrade.

GitHub: https://github.com/KatarinaKozjak

