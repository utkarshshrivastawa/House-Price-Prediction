# House Price Prediction using XGBoost Regression

## Dataset Overview
The Boston Housing dataset contains information collected by the U.S Census Service concerning housing in the area of Boston Mass. It has 506 entries with 14 attributes. The attributes include crime rate, average number of rooms per dwelling, accessibility to highways, etc.

## Data Preparation
1. Missing Values: The dataset was checked for missing values, and none were found, making it ready for model training without needing imputation.
2. Feature Selection: All the features were used for prediction except for the 'price' column, which is our target variable.
3. Train-Test Split: The dataset was split into training and testing sets to evaluate the model's performance accurately.

## Model Training
1. Algorithm: XGBoost Regression, known for its performance and speed.
2. Training: The XGBRegressor model was trained with the training set.

## Model Evaluation
1. Evaluation Metrics: The model was evaluated using R squared error and Mean Absolute Error on both training and testing data.
2. Results:
          1. Training Data: R squared error of approximately 0.999, indicating that the model explains all the variability of the response data around its mean.
          2.Testing Data: R squared error of approximately 0.905, indicating a high level of prediction accuracy on unseen data.
## Predictive System
A sample input data point was used to predict the house price using the trained XGBoost model. The model predicted a house price close to the actual value, demonstrating its potential for real-world applications.

## Visualization
Price Prediction: A scatter plot was used to visualize the actual vs. predicted prices, showing a strong correlation and model accuracy.
## Conclusion
The XGBoost Regression model proved highly effective in predicting house prices based on various features with a high degree of accuracy. This model can be a valuable tool for real estate price estimation, investment analysis, and understanding the housing market dynamics.

## Contributions
Contributions are welcome! If you have suggestions for improving the model or additional features to consider, feel free to fork the repository, make your changes, and submit a pull request.
