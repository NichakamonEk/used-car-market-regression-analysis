# Used Car Market Analysis — Identifying Undervalued Vehicles

▪️ Business analytics project focused on identifying undervalued used cars using regression analysis  
▪️ Designed to support acquisition decisions and profitability in the secondary car market  

---

## ▸ Project Overview
This project analyses the used car market to identify vehicles priced below their estimated market value.  
The objective is to support data-driven acquisition decisions by estimating fair prices and flagging undervalued opportunities with strong resale potential.

---

## ▸ Business Context
**Used Cars R Us Pvt Ltd** is a used car purchasing company operating in India, specialising in acquiring cars from individual sellers and reselling them to dealers.

**Key Business Question:**  
Which cars are undervalued relative to market fundamentals and represent profitable acquisition opportunities?

---

## ▸ Data Overview
- Dataset: Used car listings (1,997 records)
- Key variables:
  - Car age
  - Kilometers driven
  - Fuel type
  - Transmission type
  - Number of owners
  - Selling price

---

## ▸ Analytical Approach
- Exploratory data analysis to understand key price drivers
- Visual analysis of relationships between price, age, and mileage
- Correlation analysis to assess variable relationships
- Regression modelling with:
  - Log-transformed selling price and mileage
  - Dummy variables for fuel type and transmission
  - Controls for age and ownership

---

## ▸ Regression Model
- Objective: Estimate fair market value of used cars
- Key predictors:
  - Car age
  - Kilometers driven (log)
  - Transmission type
  - Fuel type
  - Number of owners
- Model performance:
  - R-squared ≈ 69%, indicating strong explanatory power

---

## ▸ Identifying Undervalued Cars
Cars were classified as undervalued using two criteria:
- **20% threshold:** Actual price at least 20% below predicted value
- **95% lower bound:** Actual price below the lower bound of the prediction interval

These rules balance opportunity identification with model uncertainty.

---

## ▸ Key Findings
- A meaningful subset of cars is priced below estimated market value
- Automatic transmission vehicles show higher resale potential
- Age and mileage are the strongest negative price drivers
- Certain configurations offer higher-margin acquisition opportunities

---

## ▸ Business Recommendations
- Prioritise acquisition of cars that:
  - Are priced ≥20% below predicted market value
  - Fall below the 95% lower prediction bound
  - Meet acceptable age and mileage thresholds
- Use model outputs as a screening tool before inspection and negotiation

---

## ▸ Tools & Skills
- Excel (data cleaning and regression analysis)
- Statistical modelling and interpretation
- Business-focused analytical reasoning
---

## ▸ Repository Contents
- `used-car-market-analysis-presentation.pdf` — Final analytical report and findings  
- `used-car-dataset.csv` — Dataset used for analysis  
