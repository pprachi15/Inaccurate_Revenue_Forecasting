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

**Portfolio Level Evaluation** : Comparing total forecasted revenue with actual revenue to understand overall trend alignment.

**Product Level Accuracy** : Using metrics such as MAPE and bias to identify which products have higher error and why.

**Model Version Performance** :  Evaluating forecast accuracy across model versions to assess whether upgrades improved performance.

**Monthly Stability Analysis** : Checking how error changes throughout the year to uncover seasonal weaknesses.

**Product and Version Heatmap** : Understanding which model version performs best for each product category.

**Driver Analysis** : Examining whether macro demand or marketing ratio contribute to forecasting error.

**Calibration Layer** : Applying a simple and effective correction step that uses historical error patterns to improve accuracy immediately.

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
<img width="986" height="487" alt="image" src="https://github.com/user-attachments/assets/c906ece7-e3e6-437d-b061-b0915d1efe69" />

* Forecast accuracy by product
<img width="686" height="487" alt="image" src="https://github.com/user-attachments/assets/d8bde3cd-5464-4acd-be50-a67e05dae906" />

* Forecast performance by model version
<img width="686" height="487" alt="image" src="https://github.com/user-attachments/assets/a9e7a9ad-e30b-47bf-afb0-59fe5f5bcf36" />

* Version performance through time
<img width="886" height="472" alt="image" src="https://github.com/user-attachments/assets/8eed367f-b987-4c56-81f5-922156b41fb2" />

* Product and version heatmap
<img width="685" height="487" alt="image" src="https://github.com/user-attachments/assets/6b07ce74-1eac-4a58-a569-709c4e9715ff" />

* Error versus macro demand
<img width="686" height="487" alt="image" src="https://github.com/user-attachments/assets/13166193-3821-4054-83f9-951415caa848" />

* Error versus marketing ratio
<img width="686" height="487" alt="image" src="https://github.com/user-attachments/assets/fe605501-48bc-4c4a-bb67-bf362dd812e8" />

* Calibration improvement comparison
<img width="686" height="487" alt="image" src="https://github.com/user-attachments/assets/3ad2f5f3-156b-443a-891b-2d1c1bee7db7" />
<img width="686" height="487" alt="image" src="https://github.com/user-attachments/assets/aa71251c-90ab-469a-94e3-a39b3d4b349a" />
<img width="686" height="487" alt="image" src="https://github.com/user-attachments/assets/f33a1446-8321-4bcc-ad89-9ac12e813d95" />

---

## Notebook  

The complete analysis and Python code are available in the notebook included in this repository.

---

## Part of 30 Day Applied Business Strategy Challenge

This project is Day One of "30 Day Applied Business Strategy Challenge", a thirty day challenge where I solve one real world business problem each day. The aim is to build a portfolio that reflects clear thinking, structured problem solving, and decision ready insights.

---
