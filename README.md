# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
- Vehicle length and ground clearence provided non-random amount of variance to mpg values.
- Slope of the linear model is not considered to be zero because p-value was significantly small.
- This linear model is good to predict mpg of MechaCars effectively because the R-squared value oobtained from this model is 0.7149, which ultimately is the definition of a strong correlation.

## Summary Statistics on Suspension Coils
- Screenshots are submitted above as files "totalsummary.PNG" and "lotsummary.PNG".
- According to design constraint, variance of the suspension coils must not exceed 100 pounds per square inch. The summary for all manfucaturing lots in total and lots 1 and 2 individually do not exceed this constraint. However, lot 3 does not meet the design specification as the variance obtained from lot 3 is 170.29 which is significantly greater than the maximum limit of 100 pounds per square inch.

## T-Tests on Suspension Coils
- Screenshots are submitted above as files "individualmanufacturinglot.PNG" and "allmanufacturinglots.PNG".
- According to the tests, the p-values obtained from t-tests across all manufacturing lots and for lots 1 and 2 are above the assumed significance level of 0.05 percent, which would allow us to fail to reject the null hypothesis. From lot 3, p-value of 0.04168<0.05, therefore we would reject the null hypothesis.
