# Regression Analysis — Demand Forecasting & Customer Satisfaction Modeling

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=flat&logo=microsoft-excel&logoColor=white)
![Domain](https://img.shields.io/badge/Domain-Predictive%20Analytics-0078D4?style=flat)
![Method](https://img.shields.io/badge/Method-Linear%20%26%20Multiple%20Regression-2ea44f?style=flat)
![Status](https://img.shields.io/badge/Status-Complete-2ea44f?style=flat)

## Overview

A series of regression analyses applied to three distinct business datasets — fitness customer satisfaction, cupcake demand forecasting, and avocado price modeling. Demonstrates the full regression workflow: data exploration, model building, coefficient interpretation, forecasting, and error analysis.

---

## Datasets & Models

### Model 1 — Customer Satisfaction (Rippedbody.com)
**Business question:** What drives customer satisfaction scores on a fitness information website?

- **Dataset:** Customer survey data with demographic variables (age categories) and satisfaction scores (7-point scale)
- **Method:** Multiple regression with categorical dummy variables
- **Output:** Coefficient estimates showing which age group and behavioral factors most predict satisfaction
- **Use case:** Customer experience optimization, churn prediction foundation

### Model 2 — Cupcake Demand Forecasting
**Business question:** A local cupcakery needs to forecast demand to optimize ingredient ordering and staffing.

- **Dataset:** Historical sales data over multiple periods
- **Method:** Linear regression + time trend modeling
- **Output:** Demand forecast with confidence intervals, error metrics (MAE, RMSE)
- **Use case:** Inventory planning, demand-driven operations

### Model 3 — Avocado Price Modeling
**Business question:** What factors predict avocado prices across markets?

- **Dataset:** Multi-variable avocado pricing data (volume, region, season)
- **Method:** Multiple regression with continuous and categorical predictors
- **Output:** Price prediction model, feature importance via coefficients
- **Use case:** Commodity pricing, supply chain analytics

---

## Model Performance Summary

| Model | R² | Key Predictor | Business Insight |
|-------|----|---------------|-----------------|
| Customer Satisfaction | ~0.82 | Age category + engagement | Younger users (<20) significantly less satisfied — UX gap |
| Cupcake Demand | ~0.88 | Time trend + seasonality | Demand grows ~4% QoQ with holiday spike in Q4 |
| Avocado Pricing | ~0.79 | Volume + region | West Coast markets command 18% price premium |

---

## Full Regression Workflow Applied

1. **Exploratory Data Analysis** — distributions, outliers, correlation matrix
2. **Variable selection** — multicollinearity check, VIF analysis
3. **Model estimation** — OLS regression via Excel Data Analysis ToolPak
4. **Output interpretation** — coefficients, p-values, R², F-statistic
5. **Forecasting** — applying fitted model to new input values
6. **Error analysis** — residual plots, MAE, RMSE, forecast accuracy

---

## Skills Demonstrated

- Linear and multiple regression modeling
- Dummy variable encoding for categorical predictors
- Model evaluation (R², adjusted R², p-values, F-test)
- Demand forecasting and error measurement
- Excel: Data Analysis ToolPak, regression output interpretation, residual charts

---

## Tools Used

- Microsoft Excel (Data Analysis ToolPak — Regression)
