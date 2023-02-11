# Sales_Project_LT
It seems that XGB algorithm is performing better than Lasso regression, Linear Regression,
Feed forward neural network However, the time of training the model for lasso regression is 
by far less than the Extreme Gradient Boosting algorithm (XGB). But here we care only for the 
performance factor instead of time factor.
The OLS (Ordinary Least Squares) Regression Results are a summary of a statistical model. The model is used to estimate the relationship between the dependent variable (Output) and several independent variables (Season, Location, Competetion_in_Market, Marketing, Consumer_Bahviour, Discounted_price, Product_Quality, Product_Availability, Probabilty_of_sale, Recession, Self_location, No_of_shelf, Essential_product, Product_Medicines, Product_Milk, Product_Sugar, Product_candies).

The R-squared (uncentered) value is 1.000, which indicates that the independent variables in the model explain 100% of the variation in the dependent variable. The adjusted R-squared is also 1.000, which means that all the independent variables are significant predictors of the dependent variable.

The F-statistic value of 1.164e+19 and a probability of 7.58e-305 indicate that the overall model is statistically significant. This means that at least one of the independent variables is related to the dependent variable.

The log-likelihood value of 1034.9, the AIC (Akaike Information Criterion) value of -2036, and the BIC (Bayesian Information Criterion) value of -2003 are measures of goodness of fit of the model. A lower AIC and BIC value indicates a better fit of the model.

The coef column shows the estimated coefficients of the independent variables in the model. The std err column shows the standard error of the coefficients. The t-value column shows the t-statistic of each coefficient, which is a measure of the significance of each coefficient. The p>|t| column shows the p-value of each coefficient, which indicates the level of significance. The [0.025, 0.975] column gives the 95% confidence interval for each coefficient, which shows the range of values that the true coefficient is likely to fall in.

