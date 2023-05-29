# Linear-Regression-with-Statsmodels

## Background

I created this notebook to demonstrate multiple linear regression using statsmodels.

I use synthetic data containing money spent on TV, radio and newspaper advertisements and the corresponding sale values. All units are in thousands of dollars. 

**Tools:**
* pandas
* statsmodels
* matplotlib
* seaborn

## Definition
**Multiple Linear Regression** is a technique that estimates the relationship between 1 continuous dependent variable (`y`) and 2 or more independent variables (X1,...Xn).

## Assumptions
Some statements must hold true to justify the use of linear regression:
* `Linearity` - Each independent variable is linearly related to the dependent variable.
* `Normality` - The residuals are normally distributed
* `Independent observations` - Each observation is independent.
* `Homoscedasticity` - The variation of residuals is constant across the model.
* `No multicollinearity` - No two independent variables can be highly correlated.

* The first four assumptions are for both simple and multiple linear regression. For obvious reasons, `no multicollinearity` comes into play only when tackling multiple linear regression.

## Evaluation metrics
For this demonstration, I picked `R-squared` are the evaluation metric.

Also known as `coefficient of determination`, $R^{2}$ measures the proportion of variation in the dependent variable explained by the independent variable(s).

$R^{2}$ ranges from `0-1`. The higher the $R^{2}$ the better. An $R^{2}$ of 1 means that the independent variables explains $100\%$ of the variation in the dependent variable.

For more, check out the attached notebook.

## Acknowledgements
`Google Advanced Data Analytics Professional Certificate`
