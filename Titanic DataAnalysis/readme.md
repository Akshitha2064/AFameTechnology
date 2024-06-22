This project predicts whether a passenger on the Titanic survived or not using a logistic regression model.

Project Description
The goal of this project is to build a machine learning model to predict the survival of passengers on the Titanic using features such as age, gender, ticket class, and fare.

Steps Performed
Data Preprocessing:

Dropped irrelevant columns (Cabin, Name, Ticket).
Filled missing values in the Age column with the median age.
Filled missing values in the Embarked column with the mode.
Encoded categorical variables (Sex, Embarked) using one-hot encoding.
Feature Engineering:

Created a new column Fare_Range by dividing the Fare column into 4 bins.
Model Training:

Split the data into training and test sets.
Trained a logistic regression model.
Model Evaluation:

Predicted on the test set.
Created and displayed the confusion matrix.
Calculated and printed the accuracy score.
