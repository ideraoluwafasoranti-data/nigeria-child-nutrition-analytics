# An Analysis of Infant Dietary Diversity and Childhood Wasting in Nigeria

## Project Overview
This project analyzes data from the 2024 Nigeria Demographic and Health Survey (DHS) to examine associations between infant and young child feeding practices and wasting among children aged 6 to 23 months across Nigerian states.

The analysis uses standard WHO/UNICEF IYCF indicators, specifically Minimum Dietary Diversity (MDD) and unhealthy food consumption, to assess diet quality at the population level. 

Survey-weighted logistic regression is used to account for the complex sampling design of the DHS, ensuring estimates are nationally representative.

The goal is to understand how diet quality in early life relates to acute malnutrition outcomes across different geopolitical zones in Nigeria, with attention to regional variation.

## Technical Details
Language: R
Key packages: tidyverse, haven, survey
Statistical methods: Descriptive statistics, cross-tabulation, survey-weighted logistic regression
Data source: 2024 Nigeria DHS, accessed via the DHS Program data request portal

## Project Files
nutrition_analysis.R - data cleaning, indicator construction, and regression model
nutrition_chart.png — visualization of wasting prevalence by dietary diversity category across regions

Note
This is secondary data analysis using publicly available microdata. DHS data access was granted for academic research purposes.
