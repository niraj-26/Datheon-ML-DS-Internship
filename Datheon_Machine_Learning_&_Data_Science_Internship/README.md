# Datheon Machine Learning & Data Science Internship

This repository contains my completed projects for the Datheon Machine Learning & Data Science Virtual Internship.

## Projects

### Task 1: Iris Flower Classification
**Objective:** Classify Iris flowers into Setosa, Versicolor, or Virginica using flower measurements.

**Techniques used:**
- Exploratory data analysis and visualization
- Train-test split and feature scaling
- Logistic Regression and Decision Tree
- Accuracy, precision, recall, F1-score, and confusion matrix
- Decision-boundary visualization

**Project files:** [`Task_1_Iris_Classification/`](Task_1_Iris_Classification/)

### Task 2: California Housing Price Prediction
**Objective:** Predict median house values using California housing data and compare regression models.

**Techniques used:**
- Exploratory data analysis and correlation analysis
- Feature engineering
- Train-test split and preprocessing
- Ordinary Least Squares (Linear Regression), Ridge, and Lasso Regression
- GridSearchCV for hyperparameter tuning
- RMSE, MAE, R², actual-vs-predicted plot, and residual analysis

**Project files:** [`Task_2_House_Price_Prediction/`](Task_2_House_Price_Prediction/)

## Tools & Libraries
- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn
- Jupyter Notebook

## Repository Structure

```text
Datheon_Machine_Learning_&_Data_Science_Internship/
├── README.md
├── Task_1_Iris_Classification/
│   ├── README.md
│   ├── iris_classification.ipynb
│   └── iris.csv
└── Task_2_House_Price_Prediction/
    ├── README.md
    ├── house_price_prediction.ipynb
    └── housing.csv
```

## How to Run
1. Install Python and Jupyter Notebook, or use VS Code with the Python and Jupyter extensions.
2. Install the required packages:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Open the relevant `.ipynb` notebook.
4. Ensure the corresponding dataset file is available in the same project folder.
5. Run the notebook cells from top to bottom.

## Notes
- The notebooks document the analysis, model training, and evaluation process.
- Model scores can vary if the data split, preprocessing, or model settings are changed.
