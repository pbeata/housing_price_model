# Housing Price Prediction Model

_In this project, we use existing housing price data to develop machine learning models for predicting future home prices._

* Developed regression models using real estate data from the 2011 [Ames Iowa Housing Data](https://www.kaggle.com/marcopale/housing) on Kaggle containing 2930 observations and 81 fields (features)
* Performed exploratory data analysis (EDA) with NumPy, Pandas, and Seaborn to understand the missing data and observe which features have strong correlations with the final sale price 
* Completed full data preprocessing by systematically handling all missing values in the raw data set: removed outlier observations (3) and filled all null values with either "0", "None", or a statistical estimate (e.g., mean), depending on the appropriate choice for each feature.
* Used Scikit-learn to develop regression models using an elastic net model, ridge and lasso regularization, ordinary linear regression, and a random forest regressor 
* Performed grid search cross validation to find optimal values of hyperparameters
* Employed lasso regression and achieved mean absolute error (MAE) of $14,191 and RMS error of $20,554, where the average house price in the data set was $180,815 (relative MAE = 7.8%) 

![](linear_house_model_results.png)
