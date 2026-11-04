# Neural Networks – Breast Cancer Classification Using MLP

## Project Overview

This project implements a Multilayer Perceptron (MLP) neural network to classify breast tumors as benign or malignant based on numerical tumor characteristics.

The project was developed as part of Artificial Intelligence coursework at the Faculty of Organizational Sciences, University of Belgrade.

## Dataset

The dataset contains 569 tumor samples with 30 numerical input features.

**Target variable:** `isBenign`

- `0` – Malignant tumor (positive class)
- `1` – Benign tumor

## Methodology

1. Data loading and exploration
2. Missing-value analysis and median imputation
3. Stratified train/test split (80% / 20%)
4. Feature standardization using StandardScaler
5. Neural network architecture definition
6. Model training using stochastic gradient descent
7. Training loss visualization
8. Confusion matrix analysis
9. Classification performance evaluation

## Neural Network Architecture

The model uses the following architecture:

**30 → 64 → 32 → 1**

- Input layer: 30 numerical features
- First hidden layer: 64 neurons
- Second hidden layer: 32 neurons
- Output layer: Binary classification

The neural network is implemented using Scikit-learn's `MLPClassifier`, with the following configuration:

- Hidden layers: `(64, 32)`
- Optimizer: Stochastic Gradient Descent (`sgd`)
- Maximum iterations: 1000
- Random state: 42

## Model Evaluation

| Metric | Result |
|---|---:|
| Accuracy | 97.37% |
| Precision | 95.35% |
| Recall | 97.62% |
| F1-score | 96.47% |

### Confusion Matrix

- True Positives: 41
- True Negatives: 70
- False Positives: 2
- False Negatives: 1

The model correctly classified 111 out of 114 tumor samples in the test dataset.

## Conclusion

The Multilayer Perceptron achieved strong classification performance, with an accuracy of 97.37% and an F1-score of 96.47%.

The model correctly identified 41 out of 42 malignant tumors, demonstrating high sensitivity for the malignant class.

However, further validation on independent datasets would be required before considering the model for real-world medical applications.

## Technologies

Python, Pandas, Matplotlib, SciPy, Scikit-learn, Jupyter Notebook.

## How to Run

1. Download `MLP_Breast_Cancer.ipynb` and `breast_cancer.csv`.
2. Place both files in the same working directory.
3. Open the notebook in Jupyter Notebook or Google Colab.
4. Run all cells sequentially.

## Academic Reference

Based on Artificial Intelligence coursework at the Faculty of Organizational Sciences, University of Belgrade.
