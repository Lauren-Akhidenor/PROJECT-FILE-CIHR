# Quantifying the Economic Burden of Climate-Induced Health Risks in Nigeria

## 📑 Table of Contents
1. [Project Overview](#-project-overview)
2. [Data Source & Methodology](#-data-source--methodology)
3. [Tools](#-tools)
4. [Research Objectives](#-research-objectives)
5. [Results](#-results)
   - [Objective 1: Socioeconomic Characteristics](#objective-1-socioeconomic-characteristics-of-individuals)
   - [Objective 2: Health and Consultation Patterns](#objective-2-health-and-consultation-patterns)
   - [Objective 3: Food Security and Influencing Factors](#objective-3-food-security-and-influencing-factors)
   - [Objective 4: Regression & Predictive Modeling](#objective-4-regression--predictive-modeling)
6. [Results Dashboards & Visuals](#-results-dashboards--visuals)
   - [ArcGIS Visualizations](#arcgis-visualizations)
   - [Power BI Dashboards](#power-bi-dashboards)
   - [Python Visualizations](#python-visualizations)
7. [Insights](#-insights)
8. [How to Run](#-how-to-run)
9. [Contributing](#-contributing)

---

## Project Overview
Climate change has substantial economic and health impacts in Nigeria. Increasing incidences of floods, heatwaves, and disease outbreaks affect both **labour productivity** and **food security**. This project investigates:  

1. Socioeconomic characteristics of individuals affected by climate-induced health risks.  
2. Health consultation patterns, insurance coverage, and disease prevalence.  
3. Food security status and its socioeconomic determinants.  
4. Relationships between health costs and labour productivity through **robust regression and machine learning models**.  

Data was extracted from **National Bureau of Statistics (NBS)**, cleaned in Excel, visualized with **Power BI and ArcGIS**, and analyzed using **Python**.

---

## Data Source & Methodology
- **Dataset:** NBS microdata on individual health, labour, and food security.  
- **Data Cleaning:** CSV → Excel → cleaned for missing values, formatting, and categorical consistency.  
- **Analysis Tools:** Power BI for dashboards, ArcGIS for geospatial mapping, Python for regression and predictive modeling.  
- **Sample Size:** 135 individuals.

---

## Tools
- **ArcGIS in Power BI** – mapping disease prevalence and food insecurity across LGAs.  
- **Power BI** – dashboards of socioeconomic characteristics, health costs, and food security indicators with **AI features**.  
- **Python** – Pandas, Numpy, Statsmodels, Scikit-learn, XGBoost, Matplotlib.  

---

## Research Objectives
- Describe socioeconomic characteristics of individuals affected by climate-induced health risks.  
- Examine health consultation patterns and insurance uptake.  
- Assess food security and identify key influencing factors.  
- Model the relationship between health costs, labour productivity using regression and machine learning.

---

## Results

### Objective 1: Socioeconomic Characteristics of Individuals
- **Gender:** 78.52% male, 21.48% female.  
- **Average Age:** 41.61 years.  
- **Average Household Size:** 5–6 members.  
- **Education:** Father and Mother’s education varied by zone, with significant proportions lacking formal education.  
- **Sectoral Distribution:** North vs South, urban vs rural (visualized in ArcGIS and Power BI).

---

### Objective 2: Health and Consultation Patterns
- **Average Hours Worked:** 198.87 hours.  
- **Average Absence Due to Illness:** 0.98 days.  
- **Common Illnesses:** Malaria, typhoid, body pains, headache, ulcer/stomach pain.  
- **Consultation Places:** Hospital, clinic, chemist, home.  
- **Insurance Coverage:** Very low uptake; most individuals pay out-of-pocket.  

---

### Objective 3: Food Security and Influencing Factors

| Predictor           | Coefficient | Odds Ratio (OR) | 95% CI (OR)       | P-value | Interpretation                                           |
|--------------------|------------|----------------|-----------------|---------|---------------------------------------------------------|
| Health_Cost         | 0.0003     | 1.0003         | 0.9991 – 1.0014 | 0.642   | Not statistically significant; minor effect            |
| Days_to_stop_work   | 17.5377    | 4.03e+07       | 0 – 9.32e+07    | 0.9997  | Not significant; extremely large variability           |
| Gender_code         | 0.2700     | 1.31           | 0.093 – 18.36   | 0.841   | Gender has no significant effect                       |
| Sector              | -16.4578   | 7.11e-08       | 0 – 7.53e+03    | 0.997   | Sector effect not significant                           |
| zone_North East     | 0.3195     | 1.38           | 0.081 – 23.59   | 0.826   | Region not significant                                  |
| zone_North West     | -1.1534    | 0.32           | 0.017 – 5.84    | 0.439   | Not significant                                        |
| zone_South East     | -1.5896    | 0.20           | 0.009 – 4.40    | 0.310   | Not significant                                        |
| zone_South South    | 13.9893    | 1.19e+06       | 0 – 3.14e+03    | 0.993   | Not significant                                        |
| zone_South West     | -1.5018    | 0.22           | 0.012 – 4.13    | 0.314   | Not significant                                        |
| Constant            | 19.6601    | 3.44e+08       | 0 – 7.56e+03    | 0.996   | Baseline intercept                                      |

**Logistic Regression: Food Insecurity**
- R²: 0.165  
- Predictors: Health cost, days stopped from work, gender, sector, zone.  

**Food Insecurity Prevalence:** 16.3% of individuals experienced food insecurity. 

**Influencing Variables:** Health costs, days to stop work, gender, sector, and zone.

**Key Observations:**  
  - No predictor was statistically significant in the logit model.  
  - The prevalence aligns with descriptive counts from the dataset.

---

### Objective 4: Robust Linear Regression Model and Machine Learning

#### Robust Linear Model: Labour Productivity
| Predictor         | Coefficient | P-value | Interpretation                                         |
|------------------|------------|---------|-------------------------------------------------------|
| Age               | -40.52     | 0.028   | Older individuals have lower productivity            |
| Sector_1          | -265.41    | 0.000   | Sectoral differences strongly affect productivity    |
| Other predictors  | NS         | >0.05   | Not statistically significant                        |

- Machine Learning Models:  
  - **Decision Tree:** 100% accuracy (small test set).  
  - **Random Forest:** 97.78% CV accuracy, top features: income, borrowing food, restricted consumption.  
  - **XGBoost:** 97.04% CV accuracy
---

## Results Dashboards & Visuals

### ArcGIS Visualizations
<details>
<summary>Click to expand ArcGIS visualizations</summary>
<img src="Screenshot (951).png" width="700">
<img src="Screenshot (955).png" width="700">
</details>

### Power BI Dashboards
<details>
<summary>Click to expand Power BI visualizations</summary>
<img src="Screenshot (950).png" width="700">
<img src="Screenshot (952).png" width="700">
<img src="Screenshot (953).png" width="700">
<img src="Screenshot (954).png" width="700">
<img src="Screenshot (956).png" width="700">
<img src="Screenshot (957).png" width="700">

**AI-Enhanced Features in Power BI:**  
- **Q&A:** Ask natural language questions about food insecurity, health costs, and labour productivity.  
- **Key Influencers:** Automatically identifies variables (income, sector, zone) that most affect outcomes.  
- **Decomposition Trees:** Explore hierarchical contributions of predictors to food insecurity and productivity.  
- **Interactive Buttons:** Filter dashboards dynamically by **zone, sector, or health expenditure** for tailored insights.

</details>

### Python Visualizations
- **Feature importance** (Random Forest) for food insecurity.  
- **Predicted probabilities** of food insecurity.  
- **Distribution of labour productivity vs health costs.**  

<details>
<summary>Click to expand Python Visualizations</summary>
<img src="Screenshot (959).png" width="700">
<img src="Screenshot (958).png" width="700">
</details>

---

## Insights
- Climate-induced health risks reduce **labour productivity** and increase **food insecurity**.  
- **Sector, age, and income** are critical factors affecting productivity and food security.  
- **Policy Implications:** Focused health interventions and food support programs in vulnerable zones are essential.  
- ArcGIS and Power BI highlight **regional disparities**, enabling targeted action.

---

## 🚀
