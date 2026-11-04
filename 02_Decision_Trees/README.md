# Decision Tree – Bank Customer Churn Prediction

## Project Overview

This project applies a Decision Tree classification algorithm to predict whether a bank customer will remain with the bank or leave.

The analysis was developed as part of Artificial Intelligence coursework at the Faculty of Organizational Sciences, University of Belgrade.

## Dataset

The dataset contains information about European bank customers, including demographic characteristics, account balances, credit scores, and banking activity.

**Target variable:** `Stayed`
- `1` – Customer stayed with the bank
- `0` – Customer left the bank

## Methodology

1. Data exploration and preprocessing
2. Feature selection and analysis
3. Handling missing values
4. One-Hot Encoding of categorical variables
5. Stratified train/test split
6. Hyperparameter tuning using 10-fold cross-validation
7. Cost-complexity pruning using `ccp_alpha`
8. Decision Tree visualization
9. Model evaluation using a confusion matrix and classification metrics

## Technologies

- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn
- Jupyter Notebook / Google Colab

## Model Evaluation

The model is evaluated using Accuracy, Precision, Recall, and F1-score.

The analysis focuses on the model's ability to distinguish between customers who stay and customers who leave the bank.

## Key Findings

The Decision Tree demonstrates stronger performance in identifying customers who remain with the bank than those who leave.

This highlights the importance of examining class-specific performance, especially when developing models for customer retention.

## How to Run

1. Download the notebook and dataset.
2. Open `Decision_Tree.ipynb` in Jupyter Notebook or Google Colab.
3. Ensure that `bank.csv` is available in the working directory.
4. Run all cells sequentially.

## Academic Reference

Based on Artificial Intelligence coursework at the Faculty of Organizational Sciences, University of Belgrade.
