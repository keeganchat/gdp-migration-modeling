# Modeling GDP from Global Migration Patterns

## Overview
This project investigates the relationship between global migration patterns and GDP using regression analysis. Using data from the Pew Research Center and the World Bank Group, we built a predictive model for GDP incorporating population, migration, religion, and regional variables.

## Methods
* Wrangled and cleaned a dataset of 390 observations sampled from 12,000+ records spanning 1990–2020
* Log-transformed skewed variables to meet linearity assumptions
* Used forward stepwise variable selection to identify the best 8-variable model
* Evaluated model performance using 5-fold cross-validation and RMSE
* Achieved an adjusted $R^2$ of $0.891$, nearly 300% improvement over the null model

## Tools & Concepts
R, tidyverse, ggplot2, broom, olsrr, boot — multiple linear regression, stepwise variable selection, cross-validation

## Results
Our final model accurately predicted GDP using social and demographic factors, suggesting that economic output is closely tied to migration and population dynamics.

## Files
* gdp_migration_analysis.R — full R code
* gdp_migration_poster.pdf — data analysis poster presented at CU Boulder
