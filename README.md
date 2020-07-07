# Studying linear relationships [ ]

In this git we create two functions that allow us to loop through multiple quantile regressions using the base statsmodel function

Statsmodels' QuantReg class (https://www.statsmodels.org/dev/generated/statsmodels.regression.quantile_regression.QuantReg.html) estimates a quantile regression model using iterative reweighted least squares. When fitting a model, users provide endogenous and exogenous factors along with the quantile the model should use. 

We create a function to facilitate looping through multiple quantiles and saves the results in pandas dataframe for easy comparison and plotting. 
