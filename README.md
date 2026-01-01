# OIBSIP_DataAnalytics_task1
# House Price Prediction using Linear Regression

## Project Description
This project focuses on predicting house prices using a machine learning approach based on **Linear Regression**. The goal is to estimate house prices by analyzing various numerical features related to housing conditions.

The project uses the **Boston Housing Dataset**, which includes features such as crime rate, number of rooms, tax rate, distance from employment centers, and other factors that influence house prices. The target variable represents the median value of owner-occupied homes.

## Dataset
The dataset contains multiple numerical attributes describing housing characteristics along with the target variable **MEDV**, which represents the median house price.

## Steps Performed
1. Loaded and explored the dataset to understand its structure
2. Assigned appropriate column names to the dataset
3. Selected relevant features and defined the target variable
4. Split the dataset into training and testing sets
5. Trained a Linear Regression model using Scikit-learn
6. Made predictions on the test dataset
7. Evaluated the model using regression performance metrics
8. Visualized actual vs predicted house prices

## Tools and Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

## Model Evaluation
The model was evaluated using the following metrics:
- **Mean Squared Error (MSE)** to measure average squared prediction error
- **Root Mean Squared Error (RMSE)** to interpret prediction error in the same units as house prices
- **R-squared (R²) Score** to measure how well the model explains the variance in house prices

## Visualization
A scatter plot of actual versus predicted house prices was created to visually analyze the model’s performance. The near-linear pattern indicates reasonable prediction accuracy.

## Conclusion
The Linear Regression model was able to predict house prices with reasonable accuracy based on the given features. This project provided practical experience in data preprocessing, feature selection, regression modeling, and model evaluation. It demonstrates how linear regression can be effectively used for predicting continuous values in real-world datasets.


