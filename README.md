# Machine Learning with Python

## About This Repository

This repository contains a collection of machine learning projects developed as part of my Artificial Intelligence coursework at the **Faculty of Organizational Sciences, University of Belgrade**.

The projects demonstrate the practical application of supervised and unsupervised learning algorithms using Python.

Each project includes data preprocessing, model implementation, visualization, evaluation, and interpretation of results.

## Projects

### 01. Linear Regression – Fast Food Nutrition Analysis

**Objective:** Predict the protein content of fast-food products based on their nutritional characteristics.

**Dataset:** Fast-food nutritional information.

**Methods and Techniques:**
- Exploratory data analysis
- Missing-value handling
- Correlation analysis
- Multiple linear regression using Ordinary Least Squares (OLS)
- Regression diagnostics and residual analysis
- Model evaluation using R² and RMSE

**Results:**
- R² Score: 0.876
- RMSE: 6.02

The model explains approximately 87.6% of the variation in protein content on the evaluated dataset.

[View Project](./01_Linear_Regression/)

---

### 02. Decision Trees – Bank Customer Retention

**Objective:** Predict whether a bank customer will stay with the bank based on demographic and financial characteristics.

**Dataset:** Bank customer information.

**Methods and Techniques:**
- Data cleaning and preprocessing
- Categorical feature encoding
- Decision Tree Classification
- Cost-complexity pruning
- Hyperparameter optimization using 10-fold cross-validation
- Confusion matrix analysis
- Classification metrics

**Results:**
- Accuracy: 85.41%
- Precision: 86.83%
- Recall: 96.13%
- F1-score: 91.24%

The model demonstrates strong performance in identifying customers who remain with the bank.

[View Project](./02_Decision_Trees/)

---

### 03. K-Nearest Neighbors – Spotify Streams Classification

**Objective:** Classify Spotify songs based on their streaming popularity.

Songs are classified into two categories using the `HighStreams` target variable, which indicates whether the number of streams exceeds the 75th percentile.

**Dataset:** Spotify song information.

**Methods and Techniques:**
- Exploratory data analysis
- Missing-value handling
- Feature selection
- RobustScaler normalization
- K-Nearest Neighbors (KNN) classification
- Hyperparameter optimization using 10-fold cross-validation
- Confusion matrix and classification metrics

The project demonstrates how distance-based classification can be applied to music popularity data.

[View Project](./03_KNN/)

---

### 04. Neural Networks – Breast Cancer Classification

**Objective:** Classify breast tumors as benign or malignant using a Multilayer Perceptron (MLP) neural network.

**Dataset:** Breast cancer dataset containing 569 samples and 30 input features.

**Methods and Techniques:**
- Data preprocessing and missing-value handling
- Feature standardization
- Multilayer Perceptron (MLP) classification
- Neural network architecture: 30 → 64 → 32 → 1
- Model training and loss visualization
- Confusion matrix analysis
- Classification performance evaluation

**Results:**
- Accuracy: 97.37%
- Precision: 95.35%
- Recall: 97.62%
- F1-score: 96.47%

The model correctly classified 111 out of 114 tumor samples in the test dataset.

These results demonstrate strong classification performance on the evaluated dataset, although further validation would be required for real-world medical applications.

[View Project](./04_Neural_Networks/)

---

### 05. Clustering – Spotify Songs

**Objective:** Discover groups of similar Spotify songs using unsupervised machine learning techniques.

**Dataset:** Spotify music data containing 952 songs after preprocessing.

Two clustering algorithms were explored.

#### K-Means Clustering

**Methods and Techniques:**
- Data preprocessing and feature selection
- Outlier detection and treatment
- Feature scaling
- Elbow Method for cluster selection
- K-Means clustering with K = 2 and K = 4
- Cluster visualization and interpretation

**Results:**

| Clusters | Cluster Sizes |
|---|---|
| K = 2 | 402, 550 |
| K = 4 | 173, 245, 229, 305 |

The analysis explores how different numbers of clusters affect the grouping of songs.

#### Hierarchical Clustering

**Methods and Techniques:**
- Data preprocessing and feature normalization
- Agglomerative Hierarchical Clustering
- Ward linkage and Euclidean distance
- Dendrogram visualization
- Clustering with K = 2 and K = 4
- Cluster analysis using boxplots

The project demonstrates how hierarchical clustering can reveal relationships between songs and how dendrograms support the exploration of different cluster structures.

[View Project](./05_Clustering/)

---

## Technologies and Libraries

**Programming Language:** Python

**Data Analysis:**
- Pandas
- NumPy
- SciPy

**Data Visualization:**
- Matplotlib
- Seaborn

**Machine Learning:**
- Scikit-learn
- Statsmodels

**Development Environments:**
- Jupyter Notebook
- Google Colab

## How to Run the Projects

1. Clone the repository:

   `git clone https://github.com/KatarinaKozjak/Machine-Learning-with-Python.git`

2. Navigate to the desired project folder.
3. Install the required Python libraries.
4. Open the Jupyter Notebook file in Jupyter Notebook or Google Colab.
5. Make sure the corresponding CSV dataset is available in the correct directory.
6. Run all cells sequentially.

## Key Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Feature Selection and Feature Scaling
- Regression and Classification
- Neural Network Implementation
- Unsupervised Learning and Clustering
- Cross-Validation and Hyperparameter Tuning
- Model Evaluation and Interpretation
- Data Visualization
- Python Programming

## Academic Background

These projects were completed as part of the Artificial Intelligence course at the Faculty of Organizational Sciences, University of Belgrade.

The repository serves as a practical portfolio demonstrating my understanding of fundamental machine learning algorithms and their application to real-world datasets.
