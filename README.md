Analysis Overview

- The purpose of the analysis was to identify high and low risk borrowers based on a set of features provided in a lending_data.csv
- The data was based on a set of parameters such as loan size, interest rate and income of the borrowers.  The goal is to predict whether or not the borrower is a 'high risk' target
- The value percentage of the low and high risk targets were 97% and 3% respectively

 Machine Learning Breakdown
   - In order to properly build a model, the data needed to split into a training and testing data sets
   - The training data was fitted with a logistic regression model (this model is used primarily as a 'yes' or 'no' prediction specialist, perfect)
   - After the model was trained, it was fitted against the test data in order to make predctions
   - A confusin matrix was then created to visualize the accuracy the model exhibited in predicting low and high risk borrowers
