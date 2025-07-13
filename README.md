# Predicting Used Ford Car Prices in the UK

This project uses statistical modeling to analyze the factors influencing the pricing of used Ford vehicles in the UK. It was completed as part of the STAT 512 course and includes a full report, R code, and a final presentation.

## Overview

The project investigates three key research questions:

1. How do fuel type and road tax interact to affect Ford vehicle prices?
2. How does transmission type, in combination with fuel efficiency (MPG), influence price?
3. Can age and mileage alone predict price accurately?

A variety of regression techniques were applied, including:

- Multiple Linear Regression  
- Weighted Least Squares (WLS)  
- Robust Regression  
- Box-Cox Transformation  
- Ridge Regression  
- 10-fold Cross-Validation  
- Diagnostic tests (Shapiro-Wilk, Breusch-Pagan, influence measures)

## Key Findings

- **Fuel Type & Road Tax**: Electric and hybrid vehicles with higher taxes tend to command higher prices, likely due to market preferences and environmental incentives.
- **Transmission & MPG**: Semi-automatic transmissions are associated with higher prices despite lower fuel efficiency, possibly reflecting their presence in higher-end models.
- **Age & Mileage**: Both are statistically significant predictors of price, with higher age and mileage lowering vehicle value. A WLS model improved fit and reduced heteroscedasticity.

## Repository Structure

### /code/
- R code.pdf  
- R code.docx

### /report/
- final report.pdf  
- final report.docx  
- exploratory data analysis.pdf  
- exploratory data analysis.docx  
- presentation.pdf  
- presentation.pptx

## Tools and Packages

- Language: R  
- Libraries: `tidyverse`, `car`, `MASS`, `caret`, `glmnet`  
- Skills: Regression modeling, model diagnostics, hypothesis testing, data visualization
