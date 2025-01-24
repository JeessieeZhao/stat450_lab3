# stat450_lab3
To test the relationship between bill length and bill depth within species, a linear regression model can be used. The model should account for species as a grouping variable to control for inter-species differences.

The beta_0 refers to the intercept. The beta_1 measures the effect of bill length on bill depth, holding species constant. And the beta_2 captures differences between species clusters.

After fitting the model, we would have to verify that the residuals should have constant variance (homoscedasticity). And, the relationship between bill length and bill depth is linear within each species. Also, check there is no multicollinearity between variables (bill length and species).
