# California Housing Price Prediction

## Project Overview
This project predicts median house values using the California Housing dataset. It compares Ordinary Least Squares (OLS), Ridge Regression, and Lasso Regression.

## Dataset
- 20,640 rows
- 8 original input features
- 1 target column: `MedHouseVal`
- 3 engineered features added during preprocessing

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook

## Methodology
1. Loaded and explored the California Housing dataset.
2. Analyzed descriptive statistics, correlations, and target distribution.
3. Engineered three ratio-based features.
4. Split data into 80% training and 20% testing sets.
5. Applied median imputation and feature scaling using a preprocessing pipeline.
6. Trained OLS, Ridge, and Lasso regression models.
7. Tuned Ridge and Lasso alpha values using GridSearchCV with 5-fold cross-validation.
8. Evaluated models using RMSE, MAE, and R².
9. Visualized actual versus predicted values and residuals.

## Final Test Results

| Model | RMSE | MAE | R² |
|---|---:|---:|---:|
| OLS | 0.6738 | 0.4874 | 0.6535 |
| Tuned Ridge | 0.6739 | 0.4874 | 0.6535 |
| Tuned Lasso | 0.6740 | 0.4874 | 0.6533 |

OLS achieved the lowest test RMSE among the three evaluated models. The performance differences were small.

## Best Hyperparameters
- Ridge alpha: 10
- Lasso alpha: 0.001

## How to Run
1. Install the required Python libraries.
2. Open `house_price_prediction.ipynb` in VS Code or Jupyter Notebook.
3. Run all notebook cells from top to bottom.

## Conclusion
The three models produced similar results on the held-out test set. OLS performed marginally better according to RMSE and R² in this experiment.
