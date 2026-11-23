# Decision Log – Big Mart Sales Prediction

## 1. Algorithm Selection
I selected Multiple Linear Regression because the target variable, Item_Outlet_Sales, is continuous and the project focuses on predicting sales.

## 2. Data Preprocessing
I performed data cleaning and preprocessing to handle missing values and prepare numerical and categorical features for model training.

## 3. Feature Selection
I used product-related and outlet-related features to understand their relationship with sales and improve prediction performance.

## 4. Model Comparison
I compared Single Linear Regression with Multiple Linear Regression to evaluate whether using multiple features improved prediction performance.

## 5. Model Evaluation
I evaluated the model using MAE, MSE, RMSE, R² and Adjusted R² to understand prediction errors and model performance.

## 6. Multicollinearity
I used Variance Inflation Factor (VIF) to examine multicollinearity among the numerical input features.

## 7. Final Decision
I selected Multiple Linear Regression as the final model because it achieved an R² score of approximately 0.5793 in my reported evaluation and performed better than the single-feature baseline.
