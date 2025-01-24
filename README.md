# stat450_lab3
From the plot, I find that there is a positive relationship, but within species. 

To test the relationship between bill length and bill depth within species, a linear regression model can be used. The model should account for species as a grouping variable to control for inter-species differences.

### Model Formula:
**BillDepth = β₀ + β₁ × BillLength + β₂ × Species + ϵ**

- **β₀** refers to the intercept.  
- **β₁** measures the effect of bill length on bill depth, holding species constant.  
- **β₂** captures differences between species clusters.

### Additional Notes:
After fitting the model, we would have to verify the following:
1. The residuals should have constant variance (*homoscedasticity*).  
2. The relationship between bill length and bill depth should be linear within each species.  
3. There should be no multicollinearity between variables (bill length and species).
