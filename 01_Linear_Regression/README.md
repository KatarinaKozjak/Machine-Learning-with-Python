# Linear Regression – Fast Food Protein Prediction

## Project Overview
This project applies multiple linear regression to predict the protein content of fast-food items based on their nutritional characteristics.

The analysis was completed as part of Artificial Intelligence coursework at the Faculty of Organizational Sciences, University of Belgrade.

## Objectives
- Explore and preprocess nutritional data.
- Analyze correlations between numerical variables.
- Build an Ordinary Least Squares (OLS) regression model.
- Predict protein content using cholesterol, calories, and sodium.
- Evaluate model performance using R² and RMSE.
- Examine regression assumptions and multicollinearity.

## Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Statsmodels
- Scikit-learn
- SciPy
- Google Colab / Jupyter Notebook

## Results
The model achieved the following evaluation results:

| Metric | Value |
|---|---|
| R² | 0.8758 |
| RMSE | 6.02 |
| RSS | 3733.69 |
| TSS | 30054.72 |

The model explains approximately 87.58% of the variability in protein content on the evaluated dataset. Regression diagnostics were also performed to investigate residual behavior, influential observations, and potential violations of model assumptions.

## Dataset
The analysis uses `fastfood.csv`.

## Academic Reference
This project is based on university coursework in Artificial Intelligence.
