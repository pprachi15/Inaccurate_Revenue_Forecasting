# Inaccurate Revenue Forecast Analysis  
### A practical business problem solved through forecasting evaluation and calibration

---

## Overview  

This project explores a common challenge in fintech, banking, and consulting environments: inaccurate revenue forecasting. Forecasting impacts planning, budgeting, hiring, marketing decisions, investor communication, and overall business strategy. When forecasts diverge from actuals, multiple teams feel the impact.

This project follows the same structured workflow used by real forecasting and strategy teams to evaluate errors and identify opportunities for improvement.

---

## Business Problem  

The company is experiencing inconsistencies between predicted and actual revenue. Leadership needs clarity on several key questions that directly influence operational and financial planning.

These questions include  
1. How accurate is the overall portfolio forecast  
2. Which products contribute most to forecasting error  
3. Did newer model versions perform better than previous ones  
4. Are errors stable throughout the year or concentrated in specific months  
5. Do macro demand shifts or marketing intensity affect accuracy  
6. Can we improve accuracy without rebuilding the entire model  

Understanding these questions helps determine whether root causes relate to product behavior, market conditions, missing features, or model design.

---

## Approach  

This analysis follows a practical, business oriented structure.

### Portfolio Level Evaluation  
Comparing total forecasted revenue with actual revenue to understand overall trend alignment.

### Product Level Accuracy  
Using metrics such as MAPE and bias to identify which products have higher error and why.

### Model Version Performance  
Evaluating forecast accuracy across model versions to assess whether upgrades improved performance.

### Monthly Stability Analysis  
Checking how error changes throughout the year to uncover seasonal weaknesses.

### Product and Version Heatmap  
Understanding which model version performs best for each product category.

### Driver Analysis  
Examining whether macro demand or marketing ratio contribute to forecasting error.

### Calibration Layer  
Applying a simple and effective correction step that uses historical error patterns to improve accuracy immediately.

---

## Key Insights  

* Forecasts follow overall trends but miss important seasonal movements  
* Certain products contribute more to portfolio error due to volatility  
* Newer model versions are not always more accurate  
* Macro demand has a noticeable impact on forecasting stability  
* Marketing ratio has limited observed influence  
* Calibration significantly improves accuracy with minimal complexity  

---

## What I Learned  

* Forecast errors often follow predictable patterns  
* Product level evaluation reveals issues hidden in portfolio averages  
* External drivers are essential for robust forecasting  
* Calibration is a powerful method for rapid improvement  
* Strong communication and structure matter as much as technical code  

---

## Skills Demonstrated  

* Forecast evaluation and accuracy measurement  
* Driver correlation analysis  
* Product and version segmentation  
* Feature engineering  
* Calibration design  
* Structured reasoning and business communication  
* Clean and consistent data visualization  

---

## Visuals  

The project includes visualizations such as  
* Actual versus forecast revenue over time

* Forecast accuracy by product

* Forecast performance by model version

* Version performance through time

* Product and version heatmap

* Error versus macro demand
 
* Error versus marketing ratio

* Calibration improvement comparison
 

All visuals follow a clean and consistent JPM style theme.

---

## Notebook  

The complete analysis and Python code are available in the notebook included in this repository.

---

## Part of 30 Day Applied Business Strategy Challenge

This project is Day One of Project Thirty, a thirty day challenge where I solve one real world business problem each day. The aim is to build a portfolio that reflects clear thinking, structured problem solving, and decision ready insights.

---
