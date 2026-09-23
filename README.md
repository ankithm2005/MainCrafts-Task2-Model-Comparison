# MainCrafts AI/ML Internship – Task 2

## Feature Engineering, Model Optimization & Performance Comparison

This project was completed as part of the **MainCrafts Technology Artificial Intelligence & Machine Learning Internship**.

## Objective

The objective of this task is to apply feature scaling, train different regression models, and compare their performance on the California Housing dataset.

## Dataset

The **California Housing dataset** from scikit-learn was used for house price prediction.

The dataset contains multiple housing-related features and a continuous target representing house values.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Data Preprocessing

The following preprocessing steps were performed:

- Loaded the California Housing dataset
- Separated features and target variable
- Applied `StandardScaler` for feature scaling
- Split the dataset into training and testing sets
- Used an 80:20 train-test split

## Machine Learning Models

Three regression models were implemented:

1. Linear Regression
2. Ridge Regression
3. Decision Tree Regressor

## Model Evaluation

The models were evaluated using:

- RMSE (Root Mean Squared Error)
- R² (R-squared)

### Results

| Model | RMSE | R² |
|---|---:|---:|
| Decision Tree | 0.724234 | 0.599732 |
| Ridge Regression | 0.745554 | 0.575819 |
| Linear Regression | 0.745581 | 0.575788 |

Lower RMSE indicates smaller prediction errors, while higher R² indicates greater explained variation on the test data.

## Visualization

An Actual vs Predicted House Prices visualization was created to compare model predictions with actual values.

## Project Files

- `AI_ML_Task2_Model_Comparison.ipynb` – Jupyter Notebook containing the complete implementation
- `AI_ML_Task2_Model_Comparison_Report.pdf` – Project report

## Conclusion

The three regression models were implemented and evaluated using the same test dataset. Feature scaling and model comparison were performed using RMSE and R² metrics. The experiment demonstrates the process of training and evaluating different regression approaches for house price prediction.

## Internship

**MainCrafts Technology – Artificial Intelligence & Machine Learning Internship**
