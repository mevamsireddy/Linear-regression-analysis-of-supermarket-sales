# Linear-regression-analysis-of-supermarket-sales.
Linear regression analysis on supermarket sales data using scikit-learn, predicting sales based on product attributes and store information. Includes Jupyter notebooks/scripts for data preprocessing, model training, evaluation, and visualization.

# Overview
This project performs a linear regression analysis on a dataset related to supermarket sales. The goal is to build a predictive model that can estimate supermarket sales based on various features such as product attributes, store location, and time-related factors.

# Dataset
The dataset consists of two CSV files:
- train.csv: Training dataset containing features and the target variable (Item_Outlet_Sales).
- test.csv: Testing dataset containing features without the target variable.

# Project Structure
- supermarket_sales_analysis.py: Python script containing the linear regression analysis.
- train.csv: Training dataset.
- test.csv: Testing dataset.
- linear_regression_model.pkl: Serialized trained model saved using pickle.
- README.md: Project README file.

# Analysis Steps
1. Data Preprocessing: Read and preprocess the training and testing datasets.
2. Feature Scaling: Scale the features using StandardScaler.
3. Model Training: Train a Linear Regression model on the scaled training data.
4. Model Evaluation: Evaluate the model performance on both training and testing datasets using Root Mean Squared Error (RMSE).
5. Save Trained Model: Serialize and save the trained model using pickle.

# Results
- The trained model's coefficients and intercept are printed.
- Predictions are made on both training and testing datasets, and RMSE values are calculated to assess model performance.