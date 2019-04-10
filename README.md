# quantile_model_paramsA
A loop function to create a dataframe with quantile regressions results using the Statsmodel quantile regression function.

Statsmodels' QuantReg class (https://www.statsmodels.org/dev/generated/statsmodels.regression.quantile_regression.QuantReg.html) estimates a quantile regression model using iterative reweighted least squares. When fitting a model after users provide endogenous and exogenous factors a user chooses which quantile the model should use. 

Statmodel's function has great usage but given you usually want to compare multiple quantile fits at a time this model fitting process is routinely looped. This function loops a model through multiple quantiles and outputs a dataframe with the parameters for further analysis and easy plotting.

