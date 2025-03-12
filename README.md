#Project Title: Delivery Time Prediction Using Machine Learning

#Project Description:
This project focuses on predicting the actual delivery time using various machine learning models. The dataset contains features like OSRM time, OSRM distance, actual distance to destination, and more. The goal was to build a model that accurately predicts delivery 
times.

#Exploratory Data Analysis (EDA):

1)Checked data shape, info, and statistical summary.
2)Handled missing values by replacing them with the most frequent values.
3)Converted time columns to datetime format.


#Visualizations:

1)Boxplot: Root Type vs. Start Scan to End Scan.
2)KDE Plot: Actual Time vs. OSRM Time.
3)Scatter Plot: Actual Distance to Destination vs. Actual Time.
4)Bar Plot: Is Cutoff vs. Cutoff Factor.
5)Generated a heatmap to understand correlations after label encoding categorical columns.


#Feature Engineering:

Label-encoded categorical columns.

Selected relevant features and split the data into training and testing sets.


#Model Training and Evaluation:
The following models were trained:

1)Linear Regression
2)Decision Tree Regressor
3)Random Forest Regressor
4)Gradient Boosting Regressor
5)XGBoost Regressor


#Results:

Linear Regression: R² = 0.0975, MAE = 48.6669
Decision Tree: R² = 0.0994, MAE = 7.7904
Random Forest: R² = 0.9997, MAE = 1.8558 (Best Model)
Gradient Boosting: R² = 0.9979, MAE = 15.4023
XGBoost: R² = 0.9992, MAE = 6.5820


#Conclusion:
The Random Forest Regressor performed the best with an R² score of 0.9997 and MAE of 1.8558, making it the optimal model for this dataset.
