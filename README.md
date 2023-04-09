# Regression-Metrics

The goal of this task is to predict the price based on the available features using a linear regression model.

- All of the features and the target are continuous variables.

- Data has been cleaned previously.

- An important exploration step is to determine if there are any moderate or strong correlations in your variables.

## Data Set
The link to the data set contains information about housing prices in the Boston area in 1978. It is a modified version of a classic data set used to introduce machine learning. (https://drive.google.com/file/d/1EtNMLkPCltdm8TH_HA-c8D4L75apgzkn/view)

This is the data dictionary for this data set:

- CRIM per capita crime rate by town

- NOX nitric oxides concentration (parts per 10 million)

- RM average number of rooms per dwelling

- AGE proportion of owner-occupied units built prior to 1940

- PTRATIO pupil-teacher ratio by town

- LSTAT % lower economic status of the population

- PRICE Median value of owner-occupied homes in $1000's

## Tasks

1. Make a heatmap of the correlations. Identify any features that have a correlation coefficient of magnitude 0.5 (could be + or -) or greater with price. Limit your analysis to these three features.

2. Select ONLY the 3 features most highly correlated with price for your feature matrix (X).  

3.  Select price for your target vector (y).

4. Split your data into train and test sets. Please use the random number 42 for consistency!

5. Instantiate your model and fit it on the training set.

6. Evaluate your model performance using R^2 on the training set and on the test set. Is there a difference between model performance on the training data vs the test data?

7. Evaluate your model on both data sets using mean absolute error (MAE).

8. Evaluate your model on both data sets using mean squared error (MSE).

9. Evaluate your model performance using RMSE on the training set and on the test set. This metric is useful because the units will be in the same units as your target vector, in this case, 1,000s of dollars.
