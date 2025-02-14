Salary Prediction Using Linear Regression

-This project involves building a machine learning model to predict salaries based on various factors such as work year, experience level, employment type, job title, employee residence, and company characteristics. The dataset used includes information about salaries in USD along with other related features.

Features-
Data Preprocessing: Handling null values and duplicate records.
Ordinal Encoding: Transforming categorical data into numerical format.
Linear Regression Model: Training a linear regression model to predict salaries.
Evaluation Metrics: Computing Mean Squared Error, Root Mean Squared Error, and R-Squared Score to evaluate model performance.

Dataset-
The dataset contains 3755 rows and 11 columns with features such as:
Work year
Experience level
Employment type
Job title
Salary
Salary currency
Salary in USD
Employee residence
Remote ratio
Company location
Company size

Installation-
To run this project on your local machine, follow these steps:
-Clone the repository:
-Create a virtual environment:
-Install the required packages:
-Run the Jupyter Notebook:

Usage-
Load the Dataset: The dataset is loaded from a CSV file using Pandas.
Data Preprocessing: Null values and duplicate records are handled.
Feature Encoding: Categorical features are encoded using Ordinal Encoding.
Train-Test Split: The data is split into training and testing sets.
Model Training: A Linear Regression model is trained on the training data.
Model Prediction: Predictions are made on the test data.
Evaluation: Model performance is evaluated using Mean Squared Error, Root Mean Squared Error, and R-Squared Score.

Example Outputs-
After training the model, the following evaluation metrics are obtained:
Mean Squared Error: 1170508129.7271976
Root Mean Squared Error: 34212.68960089513
R-Squared Score: 0.7035029273293276
Model Accuracy: 0.7035029273293276

-This project demonstrates the process of building a machine learning model to predict salaries using linear regression. The model's performance is evaluated using appropriate metrics, and the results indicate a reasonably good fit.

Limitations-
The dataset may contain outliers that could affect the model's performance.
The model assumes a linear relationship between features and the target variable.

Future Enhancements-
Exploring more advanced models such as Random Forest or Gradient Boosting for better performance.
Hyperparameter tuning to improve model accuracy.
Feature engineering to extract more meaningful features from the dataset.
