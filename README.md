# PCA with Random Forest Regressor

## Project Overview
This project demonstrates how **Principal Component Analysis (PCA)** can reduce the dimensionality of a dataset and how it affects the performance of a Random Forest Regressor for salary prediction.

## Objectives
- Understand and implement PCA.
- Reduce the number of input features while retaining 95% of the variance.
- Compare model performance with and without PCA.
- Evaluate predictions using Mean Absolute Error (MAE) and R² Score.

## Technologies Used
- Python
- Pandas
- Scikit-learn
- NumPy

## Workflow
1. Load and prepare the dataset.
2. Separate input features (X) and target variable (Salary).
3. Split the dataset into training and testing sets.
4. Standardize the features using StandardScaler.
5. Apply PCA while retaining 95% of the variance.
6. Train a Random Forest Regressor with and without PCA.
7. Compare the evaluation metrics.

## Results

| Metric | Without PCA | With PCA |
|---|---:|---:|
| Mean Absolute Error (MAE) | 1628.85 | 2321.15 |
| R² Score | 0.9896 | 0.9781 |

## Conclusion
The Random Forest Regressor performed better without PCA on this dataset. It achieved a lower MAE and a higher R² Score.

PCA reduced the number of features but slightly decreased prediction performance. This demonstrates that dimensionality reduction does not always improve a model's accuracy.

## Key Learnings
- Implementing PCA using Scikit-learn.
- Understanding feature scaling and dimensionality reduction.
- Comparing regression models using MAE and R² Score.
- Evaluating the trade-off between reducing features and prediction performance.

## Author
Govind Solanki
