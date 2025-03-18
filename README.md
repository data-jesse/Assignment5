# Data 712 - Homework 5

## Overview
This project is an extension of Assignment 4, focusing on post-estimation analysis for a logistic regression model using the `mtcars` dataset.  

Key objectives:  

- Simulate model coefficients to assess uncertainty.
- Compute Average Marginal Effects (AME) for better interpretation.
- Estimate Predicted Probabilities at different mpg levels.
- Evaluate model fit using Likelihood Ratio Test, AIC, and BIC.

## Files in This Repository  
- Assignment5.Rmd -> R Markdown file containing code, analysis, and interpretations.  
- README.md -> This file, providing an overview of the project.  

## Data Used  

This analysis is based on R’s built-in `mtcars` dataset, which includes various vehicle characteristics.  

Key variables used:  

- **am (Transmission Type):** Binary outcome variable (Automatic vs. Manual).  
- **mpg (Miles per Gallon):** Fuel efficiency of the vehicle.  
- **hp_group (Horsepower Level):** Categorized as "High" vs. "Low".  
- **wt (Weight):** The weight of the vehicle.  

Key Findings

Logistic Regression Findings
- mpg is not statistically significant (p = 0.6277) -> Fuel efficiency does not strongly predict transmission type.
- wt is statistically significant (p = 0.0138) -> Heavier cars are more likely to have automatic transmissions.
- hp_group is not statistically significant, meaning horsepower alone does not determine transmission type.

Post-Estimation Findings
- Average Marginal Effects (AME) confirm that mpg has minimal impact on transmission choice.
- Predicted probabilities show higher mpg cars are less likely to be manual.
- Likelihood Ratio Test (p < 0.001) confirms that the model is statistically significant.

## View HTML version of the Report
[file:///Users/jesseyou/Documents/Data%20712/Assignment-5.html]

## View Published Report on Rpubs
[https://rpubs.com/data-jesse/1285668]
