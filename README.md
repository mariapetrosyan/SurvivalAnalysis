# SurvivalAnalysis

This repository contains code for marketing analytics utilizing survival analysis and customer lifetime value (CLV) modeling.

## Overview

This project examines customer churn through survival analysis methods and computes CLV to provide actionable insights for formulating effective marketing strategies.

## Dataset

The analysis uses the 'telco.csv' dataset. The dataset comprises various customer attributes such as region, tenure, churn, and categorical features.

## Code Overview

The main script `SurvivalAnalysis.ipynb` contains the following major components:

### Data Processing

The preprocessing steps include:

Transforming categorical variables to numerical values using label encoding.
Adjusting the dataset to suit the requirements of survival analysis models.

### Survival Analysis

The code includes fitting different parametric survival models:

- Weibull AFT Model
- LogNormal AFT Model
- LogLogistic AFT Model
- Generalized Gamma Model
- Exponential Model

The models are fitted to predict the tenure or survival time until customer churn.

### Customer Lifetime Value (CLV) Calculation

CLV calculations are performed using the LogNormal model, where CLV for each customer is determined based on their projected survival functions.

### Insights and Recommendations

From the analysis, we derive insights and offer practical recommendations for marketing strategies, which are informed by the CLV data and the outcomes of the survival analysis.



## Usage

1. Ensure you have the necessary libraries installed (`pandas`, `lifelines`, `matplotlib`).
2. Load the dataset 'telco.csv'.
3. Run the provided Python notebook `SurvivalAnalysis.ipynb` to perform the analysis.

## Results and Findings

Our findings identify critical factors that influence customer churn and CLV. A notable observation is the significant impact of the 'retire' variable on CLV, which provides a basis for targeted marketing tactics aimed at specific customer demographics.

## Conclusion

The insights obtained underscore the necessity of customized marketing approaches that leverage CLV evaluations and survival analysis findings.

## Budget Calculations

Included are budgetary calculations that consider retention rates, associated costs, and the derived annual budgets from the analysis.

Explore the Jupyter notebook for an in-depth exploration of the analysis process.
