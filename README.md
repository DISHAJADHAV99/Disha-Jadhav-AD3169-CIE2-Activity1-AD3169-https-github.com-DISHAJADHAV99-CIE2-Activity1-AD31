# predict-big-mart-item-outlet-sales
# Big Mart Sales Prediction Using Multiple Linear Regression

## 1. Project Overview
This project is part of CIE 2 – Activity 1 for the course Regression and Classification Algorithms.

The project aims to predict Big Mart product outlet sales using Multiple Linear Regression by analyzing different product-related and outlet-related features.

**Role:** Data Scientist  
**Problem Type:** Supervised Machine Learning – Regression  
**Algorithm:** Multiple Linear Regression

## 2. Objectives
- Understand and analyze the Big Mart sales dataset.
- Perform data cleaning and preprocessing.
- Conduct Exploratory Data Analysis (EDA).
- Analyze correlations between input features and sales.
- Perform manual regression calculations using the Normal Equation.
- Implement Single Linear Regression and Multiple Linear Regression.
- Interpret model coefficients and intercept.
- Evaluate model performance using regression metrics.
- Check regression assumptions and multicollinearity.
- Predict sales for a new product and outlet.

## 3. Dataset Information
- **Dataset Name:** Big Mart Sales Prediction Dataset
- **Source:** Kaggle
- **Number of Rows:** 8,523
- **Number of Columns:** 12
- **Target Variable:** `Item_Outlet_Sales`

**Dataset Source:** [Add your exact Kaggle dataset URL here]

The dataset contains information about products, item prices, visibility, outlet types, outlet sizes and sales.

## 4. Tools and Technologies
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

## 5. Project Workflow
1. Dataset loading and inspection
2. Data cleaning and preprocessing
3. Exploratory Data Analysis
4. Correlation matrix and heatmap
5. Manual Normal Equation calculation using 8 observations and 2 features
6. Train-test splitting
7. Single Linear Regression model
8. Multiple Linear Regression model
9. Coefficient and intercept interpretation
10. Model evaluation
11. Residual analysis
12. Regression assumptions checking
13. Multicollinearity detection using VIF
14. New sales prediction

## 6. Model Evaluation Results

The Multiple Linear Regression model was evaluated using the following metrics:

| Evaluation Metric | Result |
|---|---:|
| MAE | 792.02 |
| MSE | 1,143,542.15 |
| RMSE | 1,069.37 |
| R² Score | 0.5793 |
| Adjusted R² | Add final value |

*Verify these values against the final executed notebook before submission.*

## 7. Multicollinearity Analysis

Variance Inflation Factor (VIF) was used to check multicollinearity among the numerical input features.

The obtained VIF values were close to 1, indicating negligible multicollinearity among the four numerical features tested.

## 8. Key Findings
- Item MRP shows a positive relationship with Item Outlet Sales.
- The multiple-feature model achieved a test R² score of approximately 0.5793.
- The multiple-feature model performed better than the single-feature baseline in the reported evaluation.
- VIF results showed no significant multicollinearity among the numerical predictors tested.

## 9. Repository Structure
```text
Big-Mart-Sales-Prediction/
│
├── Big_Mart_Sales_Prediction.ipynb
├── Train.csv
├── README.md
└── requirements.txt
```

## 10. Conclusion
This project demonstrates the application of Multiple Linear Regression for predicting Big Mart product sales using product and outlet features.

The project provided practical experience in data preprocessing, exploratory data analysis, manual regression calculations, model development, evaluation, residual analysis and prediction.

The model has limitations because sales may also depend on factors not included in the dataset. Therefore, predictions should be treated as estimates rather than guaranteed sales values.

## 11. Limitations
- The model assumes a linear relationship between input features and sales.
- Some factors affecting sales may not be available in the dataset.
- The model may not capture complex non-linear relationships.
- Prediction accuracy depends on the quality and representativeness of the dataset.

## 12. Author
**Disha Jadhav**  
Third-Year B.Tech – Artificial Intelligence and Data Science

## 13. Faculty Reference
[complexiota – GitHub](https://github.com/complexiota)
