# Quantifying the Economic Burden of Climate-Induced Health Risks in Nigeria

---

## 📑 Table of Contents
1. [Project Overview](#project-overview)
2. [Data Source & Methodology](#data-source--methodology)
3. [Tools](#tools)
4. [Research Objectives](#research-objectives)
5. [Results](#results)
   - [Objective 1: Socioeconomic Characteristics](#objective-1-socioeconomic-characteristics-of-individuals)
   - [Objective 2: Health and Consultation Patterns](#objective-2-health-and-consultation-patterns)
   - [Objective 3: Food Security and Influencing Factors](#objective-3-food-security-and-influencing-factors)
   - [Objective 4: Regression & Predictive Modelling](#objective-4-regression--predictive-modelling)
6. [Results Dashboards & Visuals](#results-dashboards--visuals)
 [Key Study Statistics](#key-study-statistics)
7. [The Climate-Health-Productivity Nexus](#the-climate-health-productivity-nexus)
8. [Critical Findings for Intervention Design](#critical-findings-for-intervention-design)
   - [Top ML Predictors of Vulnerability](#top-ml-predictors-of-vulnerability)
   - [Significant Regression Findings](#significant-regression-findings)
9. [Demographic Profile for Targeting](#demographic-profile-for-targeting)
10. [Policy Implication](#Policy-Implication)


---

## Project Overview
Climate change is increasingly imposing economic and health burdens in Nigeria. Rising incidences of floods, heatwaves, and disease outbreaks affect **labour productivity** and **food security**.  

This study examines socioeconomic characteristics, health consultation patterns, food insecurity prevalence, and the economic consequences of climate-related health risks using robust regression and machine learning models. Analysis combines descriptive statistics, predictive modelling, and visualisation to inform policy and development interventions.

---

## Data Source & Methodology
- **Dataset:** Nigerian Bureau of Statistics (NBS) microdata on health, labour, and food security  
- **Sample:** 135 individuals; data cleaned and formatted in Excel  
- **Analysis:** Descriptive statistics | Logistic regression | Robust linear regression | Machine learning (Random Forest, XGBoost) | Development impact evaluation  
- **Variables:** Health costs, labour productivity, food insecurity, socioeconomic and regional factors  

---

## Tools
- **Power BI** – interactive dashboards with AI features for analysis of health costs and productivity  
- **Python** – Pandas, Numpy, Statsmodels, Scikit-learn, XGBoost, Matplotlib for regression, predictive modelling, and data visualisation  

---

## Research Objectives
1. Describe the socioeconomic characteristics of individuals affected by climate-induced health risks  
2. Examine health consultation patterns and insurance uptake  
3. Assess food insecurity prevalence and key determinants  
4. Model relationships between health costs, labour productivity, and socioeconomic factors  

---

## Key Results

### Socioeconomic Characteristics
- Predominantly male (**78.52%**)  
- Mean age: 41.61 years  
- Household size: 5–6 members  
- Education levels vary, significant proportion with limited formal schooling  

### Health and Consultation Patterns
- Average hours worked: 198.87  
- Average absence due to illness: 0.98 days  
- Common illnesses: malaria, typhoid, headaches, ulcers  
- Low insurance coverage; most pay out-of-pocket  

### Food Insecurity and Influencing Factors
- Prevalence: 16.3% of individuals experienced food insecurity  
- Key variables examined: health costs, days off work, gender, sector, region  
- Logistic regression indicates no variable was statistically significant, reflecting complex and heterogeneous determinants  

### Regression & Predictive Modelling
- **Robust linear regression:** Age and sector significantly affect labour productivity  
- **Machine learning:** Random Forest (97.78% CV accuracy) and XGBoost (97.04% CV accuracy) identify income, food borrowing, and restricted consumption as top predictors  

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

| Metric           | Value                    | Policy Implication                                 |
|-----------------|-------------------------|---------------------------------------------------|
| Sample           | 135 individuals         | Microdata for targeted interventions             |
| Food Insecurity  | 16.3% prevalence        | 1 in 6 households vulnerable                     |
| Avg Hours Worked | 198.87/month            | Productivity baseline to protect                 |
| Illness Absence  | 0.98 days avg           | Economic cost of climate-related health impacts  |
| ML Accuracy      | 97%+ (RF & XGBoost)    | Predictive targeting is possible                 |

---

## The Climate-Health-Productivity Nexus

Climate Events → Disease Outbreaks → Health Costs → Reduced Productivity → Food Insecurity
↓ (malaria, typhoid) ↓ ↓ ↓
Floods/Heat → Out-of-pocket spending → Lost workdays → Income loss → Hunger/Borrowing


**Interpretation:**  
Climate shocks like floods and heat waves increase disease burden, driving **health expenditures, lost workdays, income reduction, and food insecurity**.  

---

## Critical Findings for Intervention Design

### Top ML Predictors of Vulnerability
- **Income level** – Primary determinant of household resilience  
- **Food borrowing** – Early warning signal for crisis  
- **Restricted consumption** – Indicator of imminent food insecurity  

### Significant Regression Findings
- **Age** significantly affects labour productivity  
- **Sector** significantly affects labour productivity  
- Food insecurity determinants are **multifactorial**, no single variable dominates  

---

## Demographic Profile for Targeting

| Characteristic       | Finding                  | Targeting Implication                            |
|---------------------|-------------------------|-------------------------------------------------|
| Gender              | 78.52% male             | Don’t neglect 21.48% female-headed households |
| Age                 | Mean 41.61 years        | Working-age population is at risk              |
| Household Size      | 5–6 members             | High dependency ratios                          |
| Insurance Coverage  | Low                     | Out-of-pocket vulnerability                     |
| Common Illness      | Malaria, typhoid        | Preventable diseases dominate                   |

---

## Policy Implication  
- Target interventions using **income, borrowing behaviour, and consumption patterns** as early-warning indicators.  
- Focus on **working-age, high-dependency households**, and **female-headed households**. Preventive health measures for malaria and typhoid can improve productivity and reduce food insecurity.



---
