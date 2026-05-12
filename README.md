# BRFSS_Food_Security_Diabetes_Analysis 

# Association Between Food Insecurity and Diabetes Prevalence Among U.S. Adults

This repository contains an R Markdown analysis of BRFSS 2022 data examining whether food insecurity is associated with diabetes prevalence among U.S. adults after adjusting for demographic, socioeconomic, and behavioral factors.

## Research Question
Is food insecurity associated with diabetes prevalence among U.S. adults after adjusting for demographic, socioeconomic, and behavioral factors?

## Data Source
Data were obtained from the 2022 Behavioral Risk Factor Surveillance System (BRFSS), a CDC survey of U.S. adults.

## Study Variables
 Outcome: Diabetes status
 Main predictor: Food security status
 Covariates: Sex, age group, BMI category, smoking status, income, education, and employment status

## Methods
Data cleaning and recoding
Descriptive statistics
 Chi square test of independence
 Cramér’s V effect size
 Independent samples t test for age
 Multivariable logistic regression
 Odds ratios and 95% confidence intervals
 McFadden pseudo R²
 Variance inflation factors
 Hosmer Lemeshow goodness of fit test

## Main Findings
Food insecurity was associated with higher diabetes prevalence. Better food security was associated with lower odds of diabetes after adjustment. BMI and age were also strongly associated with diabetes.


## Setup
1. Install R and RStudio.
2. Install required packages: haven, dplyr, ggplot2, and pscl.
3. Place the BRFSS 2022 XPT file in data/raw/.
4. Update file paths to use relative paths.

## How to Run
1. Open BRFSS-DIABETES-ANALYSIS.Rmd.
2. Knit to HTML, Word, or PDF.
3. Review tables, models, and figures in the output folders.

## Limitations
Cross sectional design prevents causal inference.
Self reported data may include recall or reporting bias.
BRFSS survey weighting should be considered for nationally representative inference.


