# Quantifying the Economic Burden of Climate-Induced Health Risks in Nigeria: A Technical Case Study

---

## Executive Summary

Even a single day of climate-induced illness (e.g., malaria, typhoid) creates a measurable ripple effect on household food security in Nigeria.

This study applies **econometric modelling and machine learning** to connect **health shocks with labour productivity loss and food insecurity**, demonstrating how climate-related risks translate into economic vulnerability.

---

## Tech Stack
**Python (Pandas, NumPy, Statsmodels, Scikit-learn, XGBoost)** | **Power BI** | **Excel** |**Econometric Modelling**

---

## 📑 Table of Contents
1. [Project Overview](#project-overview)  
2. [Data Source & Methodology](#data-source--methodology)  
3. [Research Objectives](#research-objectives)  
4. [Analytical Framework](#analytical-framework)  
5. [Key Findings: The Productivity Drain](#key-findings-the-productivity-drain)  
6. [Food Insecurity: A Complex Outcome](#food-insecurity-a-complex-outcome)  
7. [Machine Learning Insights](#machine-learning-insights)  
8. [Technical Note: The ML Paradox](#technical-note-the-ml-paradox)  
9. [Results Dashboards & Visuals](#results-dashboards--visuals)  
10. [Key Study Statistics](#key-study-statistics)  
11. [Limitations & Future Work](#limitations--future-work)  
12. [Policy Implications](#policy-implications)  

---

## Project Overview

Climate change is increasingly imposing **measurable economic and health burdens** in Nigeria. Floods, heatwaves, and disease outbreaks reduce labour productivity and weaken household resilience.

### 📌 Study Positioning
This study is best interpreted as a **proof-of-concept (pilot analysis)** demonstrating a scalable framework for quantifying climate-health-economic linkages using microdata.

👉 The approach can be extended to larger datasets such as the **Nigerian General Household Survey (GHS)**.

---

## Data Source & Methodology

- **Dataset:** Nigerian Bureau of Statistics (NBS) microdata  
- **Sample:** 135 individuals  
- **Design:** Cross-sectional  

### Methods
- Descriptive statistics  
- Logistic regression (food insecurity)  
- Robust linear regression (productivity outcomes)  
- Machine learning (Random Forest, XGBoost)  

### Key Variables
- Health costs (proxy for economic burden)  
- Labour productivity (hours worked, absenteeism)  
- Food insecurity indicators  
- Socioeconomic and demographic factors  

---

## Research Objectives

- **Quantify** socioeconomic vulnerability to climate-induced health risks  
- **Evaluate** gaps between health consultation patterns and insurance coverage  
- **Model** the transmission of health shocks into measurable labour productivity loss  
- **Assess** food insecurity prevalence and its structural drivers  

---

## Analytical Framework

**Climate Shock Transmission Pathway:**

Climate Events → Disease Burden → Health Costs → Productivity Loss → Income Decline → Food Insecurity → Coping Strategies  

**Insight:**  
Climate shocks operate as a **chain reaction**, amplifying economic vulnerability through health-related productivity loss.

---

## Key Findings: The Productivity Drain

### The 1-Day Impact
- Average illness-related absence: **0.98 days/month**  

👉 This represents approximately:
- **~5% loss in monthly productive capacity** for low-income workers  

**Interpretation:**  
Seemingly small health shocks translate into **meaningful economic losses at scale**.

---

### Structural Barriers
- **Age** significantly affects labour productivity *(p < 0.05)*  
- **Sector** significantly affects labour productivity *(p < 0.05)*  

👉 Productivity is shaped not only by health shocks but by **structural labour inequalities**  
👉 Older and informal-sector workers are disproportionately affected

---

## Food Insecurity: A Complex Outcome

- Prevalence: **16.3% (≈1 in 6 individuals)**  

### Regression Result
No statistically significant predictors identified.

### Interpretation
- Suggests **multidimensional and systemic drivers**  
- Likely influenced by **unobserved structural factors**  
- Reflects **limited statistical power due to small sample size**

👉 This highlights the **complexity of food insecurity beyond single-variable explanations**

---

## Machine Learning Insights

### Primary Stressors
- Monthly hours worked  
- Illness frequency  

### Coping Indicators (Strongest Predictors)
- Food borrowing  
- Restricted consumption  

👉 These act as **early warning signals of household vulnerability**

---

## Technical Note: The ML Paradox

**Model Performance:**
- Random Forest Accuracy: **97.78%**  
- XGBoost Accuracy: **97.04%**

### Critical Interpretation
Given the small sample size (n=135), these high accuracy scores likely reflect **overfitting rather than generalisable predictive performance**.

### Analytical Approach
This study prioritises:
- **Feature importance** over raw accuracy  
- **Interpretability** over prediction  

👉 The goal is not *prediction* but **understanding vulnerability dynamics**

---

## Results Dashboards & Visuals

### Power BI ArcGIS Map Visualisations
<details>
<summary>Click to expand ArcGIS visualisations</summary>
<img src="Screenshot (951).png" width="700">
<img src="Screenshot (955).png" width="700">
</details>

### Power BI Dashboards
<details>
<summary>Click to expand Power BI visualisations</summary>
<img src="Screenshot (950).png" width="700">
<img src="Screenshot (952).png" width="700">
<img src="Screenshot (953).png" width="700">
<img src="Screenshot (954).png" width="700">
<img src="Screenshot (956).png" width="700">
<img src="Screenshot (957).png" width="700">
</details>

### Python Visualisations
<details>
<summary>Click to expand Python Visualisations</summary>
<img src="Screenshot (959).png" width="700">
<img src="Screenshot (958).png" width="700">
</details>

---

## Key Study Statistics

| Metric | Value | Insight |
|------|------|--------|
| Sample Size | 135 | Pilot-level evidence |
| Food Insecurity | 16.3% | Significant vulnerability |
| Avg Hours Worked | 198.87/month | Productivity baseline |
| Illness Absence | 0.98 days | Hidden economic cost |
| ML Accuracy | ~97% | Interpret with caution |

---

## Limitations & Future Work

- Small sample size (n=135) limits statistical power and generalisability  
- Cross-sectional design prevents causal inference  
- Machine learning results may reflect **overfitting**  
- Food insecurity drivers may be under-specified  

### Methodological Note
While regression models identified key trends, future iterations would benefit from **formal multicollinearity diagnostics (e.g., VIF tests)** to ensure independent variables are not masking each other's effects.

👉 This study serves as a **scalable analytical framework** for larger datasets.

---

## Policy Implications

### Core Recommendation

**Shift from reactive food aid to proactive malaria prevention as a strategy for protecting labour productivity.**

### Supporting Actions
- Use **food borrowing and consumption patterns** as early warning indicators  
- Target **informal-sector and high-dependency households**  
- Expand access to **preventive healthcare**  
- Improve **insurance coverage** to reduce out-of-pocket burden  

---

## 📌 Data Source Credit
Nigerian Bureau of Statistics (NBS)

---

## Final Note

This project demonstrates how **climate-induced health shocks translate into economic vulnerability**, and provides a **data-driven framework for designing targeted, preventive interventions**.
