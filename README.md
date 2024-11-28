# Predicting Auto Insurance Premiums Using Linear Regression

## Overview
This project investigates the prediction of auto insurance premiums using customer data and multiple linear regression models. Leveraging a dataset of real-life auto insurance policies from Spain (2015–2018), it identifies key factors influencing premium costs. The study integrates advanced data cleaning, transformation techniques, and statistical diagnostics to build accurate predictive models.

## Key Highlights
- **Dataset:**
  - Source: [Inter-university Consortium for Political and Social Research (ICPSR)](https://www.openicpsr.org/openicpsr/project/193182/version/V1/view).
  - Size: 105,555 records with 30 attributes covering demographic, vehicle, and policy specifics.
- **Objectives:**
  - Identify key predictors of premium costs.
  - Build robust regression models to estimate premiums.

- **Methods:**
  - **Data Cleaning:** Handled missing values and transformed categorical, date, and numerical variables.
  - **Feature Selection:** Focused on attributes directly influencing premium calculations.
  - **Transformations:** Applied log, square root, and Box-Cox transformations to meet linear regression assumptions.
  - **Diagnostics:** Employed residual analysis, Breusch-Pagan tests, and Cook’s distance to validate models.

- **Results:**
  - Initial models demonstrated significant heteroscedasticity and non-linearity.
  - Transformations and ridge regression improved model fit, with adjusted R² increasing to 47.5%.
  - Key predictors included vehicle value, number of claims, region, and driver experience.
  - Ridge regression addressed multicollinearity among predictors.

- **Limitations:**
  - Relatively low R² indicates unexplained variability due to external regulatory or contextual factors.
  - Challenges in interpreting transformed variables and non-intuitive results for some predictors.

## Technologies Used
- **R Programming:** Data preprocessing, statistical modeling, and diagnostics.
- **Libraries:** 
  - `lubridate` for date transformations.
  - Statistical packages for regression analysis.

## Future Work
- Exploring advanced machine learning models (e.g., neural networks) for improved predictions.
- Incorporating additional data on claim frequency and severity.

## Contributors
- **Report Writing:** Jiaying (Cindy) Liu, Marta Gonczar, Haoran (Alex) Yu
- **Code Development:** Haoran (Alex) Yu, Malek Sibai, Mingyu (Oscar) Qin

---

This project provides insights into the relationship between customer data and auto insurance premiums, making it a valuable resource for academic and industry applications.
