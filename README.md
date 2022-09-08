# Multiple Linear Regression

### Instructions:
1) Import the raw data set into a Pandas DataFrame.
2) Clean the data and remove missing values. Drop any column that is not categorical or numeric. Let our target variable be MPG.highway again. Separate the independent variables from the dependent variable.
3) Generate dummy variables for the categorical features.
4) Create a training set that's 75% of your data set and a complementary test set with the remaining 25%. Specify random_state=0.
5) Train the model using the LinearRegression class. Leave all parameters at their default values.
6) Use your model to generate predictions on the test set, then create two scatter plots: one with predicted values against actual values, and another with residuals against predicted values. Print the coefficient of determination of the model with the .score() method.
7) Print out the actual model in equation form, i.e., y = b + c1x1 + c2x2 + c3x3 + ....
