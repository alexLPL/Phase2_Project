
## Repository Structure

The following documents are for Phase 2 Project:

```
├── README.md                           <- The top-level README for reviewers of this Phase 2 project
├── Phase2_project.ipynb       			<- Jupyter notebook analysis
├── Project2_Presentation.pdf     		<- PDF Presentation 
├── data                          		<- Sources of the datasets
|-- 
```


# Project 2: Housing Price Analysis

**Authors**: Liang

## Overview

The Project is the provide business insigts about housing price in the King County to the business stakeholder 

The project has utilized public data to analyze the housing price market. Based upon the findings about Housing price and the factors of house price, recommendatios are given to the stakerholder

## Business Problem

A real estate consulting and services company helps homeowners and other customers to buy and sell properties. 
They provide services to customers to evaluate house prices and check what factors are affecting house values.

We work on the project to provide insights to this real estate company

Business insights to investigate:
Estimate house values
What factors are affecting house price? By how much ?

## Data

Sources:
King County Housing Price dataset
`kc_house_data.csv`


## Methods

Regression Modeling Analysis 
Train Linear Regression Models for Price Predictions and variable coefficients analysis


## Results

Model Performance 
Coefficient of determination score : 0.52
Root Mean Squared Error (RMSE)  : 183580
	average home price : 540,296


Feature Coeffeicinets

bedrooms              -37371.213679
bathrooms              47755.971065
sqft_living              216.159834
sqft_lot                  -0.145950
floors                 65992.506014
condition_encoded      10010.159340
grade_encoded         -10961.825614
waterfront_encoded    387030.328313
yr_built_encoded      -21906.701728
Name: Coefficients, dtype: float64

Intercept: 511735.0945469917

## Conclusions

regression models for regression analysis of housing price
Model prediction for house price 
 Model features with coefficients show the factors affecting house price


## For More Information

Please review our full analysis in [our Jupyter Notebook](./Phase2_project.ipynb) or our [presentation](./Project2_Presentation.pdf).


