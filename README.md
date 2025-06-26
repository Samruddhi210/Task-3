# Task-3 
House Price Prediction using Linear Regression:

This project involves predicting house prices using a machine learning regression model built with **Linear Regression**. The dataset used is from [Kaggle - House Price Prediction] The project includes data cleaning, exploratory data analysis (EDA), feature encoding, model training, evaluation, and saving the trained model for future use.
Dataset Information:-
- Source: [Kaggle Dataset](https://www.kaggle.com/datasets/harishkumardatalab/house-price-prediction)
- Size: ~700+ entries
- Format: CSV
- Target Variable: `Price`
- Key Features: `Area`, `Bedrooms`, `Bathrooms`, `Furnishing Status`, etc.
  
- Steps Performed:-

1. **Data Import and Cleaning**
   - Handled missing values (mean/mode imputation)
   - Dropped irrelevant columns (if any)

2. **Exploratory Data Analysis**
   - Correlation matrix and pair plots
   - Outlier analysis and distribution checks

3. **Feature Engineering**
   - Encoding categorical variables using one-hot encoding
   - Feature scaling (optional)

4. **Model Training**
   - Linear Regression model from `sklearn`
   - Split into train and test sets (80/20)
   - Hyperparameter tuning using Ridge and Lasso (optional)

5. **Model Evaluation**
   - MAE, MSE, RMSE, and R² score
   - Visualized residuals and regression line

6. **Model Saving**
   - Final model saved using `joblib`
   - Predictions exported for submission/analysis
  
 Files Included:
- `House Price India.csv` - Original dataset
- `house_price_lr_model.pkl` - Trained Linear Regression model
- `price_predictions.csv` - Actual vs Predicted values
- `house_price_prediction.ipynb` - Full Colab notebook
- `README.md` - Project documentation.



