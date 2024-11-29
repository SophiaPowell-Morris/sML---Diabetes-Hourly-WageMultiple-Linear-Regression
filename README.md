# sML---Diabetes-HourlyWage Multiple-Linear-Regression

## Diabetes Dataset 

The IV and DV are identified and assigned to the appropriate variables X and Y, respectively.

Training and testing sets are generated with an 80:20 split.

Both the MinMaxScaler and StandardScaler fit on the training set. And then they are used to transform the training and testing sets.

A Multiple Linear Regression model is generated using the training set using all IV from the dataset.

And the relevant predictions are generated for the accompaning test set.

Then all predicted values below set to the following: <0.5 == 0 and all predicted values >0.5 == 1. 

The accuracy score of the test-set is then determined. 

## Hourly Wages Dataset

The dataset the inspected by dropping columns with missing values and the hourly wage values where covered to floats.

Three plots where generated to show the correlation between the Average Hourly Wage vs. Positiom, Age and Numbe rof years Worked.

The data is split into training and testing sets with an 80:20 split.

The distribution of the variables in the testing set are investigated to determine if they provide an satisfactory representation of the distribution of the training set.

The Multiple Linear Regression model is then generated using the training set, using all IVs, and the prediction are generated using the test set.

An error plot is used to graph the predictions.

The Root Mean Squared Error and R^2 of the model is calculated and interpreted.

The MLR models equation coefficients are determined and interpreted.
