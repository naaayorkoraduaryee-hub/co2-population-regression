# CO₂ Emissions and Population Analysis (2015–2024)

This repository contains Python code used to analyze the relationship between
population size and CO₂ emissions for selected countries between 2015 and 2024.
The analysis includes data cleaning, visualization, regression modeling, and
statistical assumption testing.

## Countries Analyzed
- China  
- United States  
- Germany  
- Iceland  
- New Zealand  

## Data Source
The dataset used in this study is the **Our World in Data (OWID) CO₂ dataset**.
It contains country-level annual data on CO₂ emissions, population, and related indicators.

> Source: Our World in Data – CO₂ and Greenhouse Gas Emissions

## Methods
The following analytical steps were performed:

1. Data filtering for selected countries and years (2015–2024)
2. Exploratory data analysis and descriptive statistics
3. Time-series visualization of CO₂ emissions
4. Boxplot comparison of CO₂ distributions by country
5. Ordinary Least Squares (OLS) regression of CO₂ emissions on population size
6. Residual diagnostics:
   - Shapiro–Wilk test for normality
   - Residuals vs fitted values plot
   - Q–Q plot
7. Homogeneity of variance testing using Levene’s test
8. Welch’s ANOVA and Games–Howell post-hoc comparisons

## Repository Structure
