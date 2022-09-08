# Logistic-Regression

## General Instructions

1. Import the raw data set into a Pandas DataFrame.
2. Clean the data and remove missing values. Drop any column that is not categorical or numeric. Separate the independent variables from the dependent variables.
3. Generate dummy variables for the categorical features.
4. Create a training set that's 75% of your data set and a complementary test set with the remaining 25%. Specify random_state=0.
5. Train the model using the LogisticRegressionCV class, which has cross-validation capability built in. Use this to tune your Cs hyperparameter. What value of this hyperparameter performs best in cross-validation?
6. After cross-validation, use your model to generate predictions on the test set, then create a confusion matrix from those results. Print the Matthews correlation coefficient.
