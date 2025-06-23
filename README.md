# 🌍 Quantifying the Economic Burden of Climate-Induced Health Risks in Nigeria

> 🧪 *Analyzing how climate-related health shocks affect labour productivity and food security in Nigeria's agricultural households.*

---

## 🔍 Overview

This project evaluates the **economic burden of Climate-Induced Health Risks (CIHR)** across Nigeria using national survey data. It focuses on two key dimensions:

- 🌾 **Labour Productivity**: Impact of climate-induced health risks on agricultural output.
- 🥣 **Food Security**: Household food access amidst climate-health stressors.

---

## 📈 Analytical Models Used

| Model Type                        | Purpose                                |
|----------------------------------|----------------------------------------|
| **OLS Regression**               | Labor productivity impact              |
| **Random-Effects Logistic Model**| Food security impact                   |

- 📁 Data Source: *General Household Survey Panel (GHS-Panel) Wave 5 (2023/2024) focusing on post-planting household questionnaire*  
- ⚙️ Tools: Microsoft Excel & R studio
- 📊 Outputs: Charts & regression summaries

---

## 📊 Key Findings 

## 🧍 Socio-Economic Characteristics

- 🧑‍🌾 **Gender**: 78.49% of respondents were male, indicating male-dominated agricultural households. Female household heads were more common in the South East.

  
![Screenshot 807](https://github.com/Lauren-Akhidenor/PROJECT-FILE-CIHR/blob/main/Screenshot%20(807).png)




- 🏡 **Sector**: 89.44% of respondents were from rural areas, highlighting high vulnerability to CIHR due to healthcare and infrastructure gaps.

![Screenshot 810]((https://github.com/Lauren-Akhidenor/PROJECT-FILE-CIHR/blob/main/Screenshot%20(810).png))



- 📅 **Age**: The average age was 43.66 years. Majority were within the productive age bracket (18–47 years), linking to CIHR impact on labor force.

  
![Screenshot 811](https://github.com/Lauren-Akhidenor/PROJECT-FILE-CIHR/blob/main/Screenshot%20(811).png)





- 💍 **Marital Status**: 53% of respondents were married. Married households may face more pressure due to dependents, increasing CIHR susceptibility.


![Screenshot 812](https://github.com/Lauren-Akhidenor/PROJECT-FILE-CIHR/blob/main/Screenshot%20(812).png)





- 🎓 **Parental Education**: Over 50% of respondents’ parents had no formal education, potentially limiting their access to climate-health information.


![Screenshot 814](https://github.com/Lauren-Akhidenor/PROJECT-FILE-CIHR/blob/main/Screenshot%20(814).png)


![Screenshot 813](https://github.com/Lauren-Akhidenor/PROJECT-FILE-CIHR/blob/main/Screenshot%20(813).png)





- 💸 **Income**: The average income was ₦86,112/month, but the median was ₦25,000, indicating high income inequality and widespread poverty.


![Screenshot 815](https://github.com/Lauren-Akhidenor/PROJECT-FILE-CIHR/blob/main/Screenshot%20(815).png)





- 💼 **Employment**: a frequency of 433 respondents reported being unemployed, a critical factor increasing economic vulnerability to climate-health shocks.



![Screenshot 816](https://github.com/Lauren-Akhidenor/PROJECT-FILE-CIHR/blob/main/Screenshot%20(816).png)





- 🚑 **Access to Healthcare**: Average travel time to health facilities was 34.5 minutes. While most respondents spent <1 hour, up to 5 hours was recorded.


![Screenshot 817](https://github.com/Lauren-Akhidenor/PROJECT-FILE-CIHR/blob/main/Screenshot%20(817).png)





  ---

> 🔹 **Labour Productivity**:  
> CIHR has a **positive but statistically insignificant** effect (p = 0.741) on labour productivity.  
> This could be due to omitted socio-economic factors like access to healthcare.



![Screenshot 818](https://github.com/Lauren-Akhidenor/PROJECT-FILE-CIHR/blob/main/Screenshot%20(818).png)


-----

> 🔹 **Food Security**:  
> CIHR shows a **negative association** with food security (p = 0.164), suggesting increased health risks reduce access to food.  


![Screenshot 819](https://github.com/Lauren-Akhidenor/PROJECT-FILE-CIHR/blob/main/Screenshot%20(819).png)



-----

> 🔹 Additional Notes:
> - Gender and marital status were not significant.
> - Age negatively affected productivity (**p = 0.027**).
> - Women were 34.5% less likely to be food secure than men (**p = 0.049**).
> - Rural areas were 69% more likely to be food secure than urban.

These findings align with Akogun et al. (2021), who found sugarcane workers in Nasarawa State had increased productivity despite malaria, and Romanello et al. (2021), who noted food security vulnerability among climate-affected households.

---




## 💡 Recommendations 

To reduce CIHR and improve resilience:

- 🌱 **Adopt climate-resilient agricultural practices**
- 🛰️ **Integrate early warning systems and CIHR assessments** into policy
- 👩‍🌾 **Support gender-sensitive climate adaptation strategies**
- 🧮 **Link health and labor data** for future modeling
- 📈 **Strengthen health-labor-agriculture data collection** nationwide

---

## 👩🏽‍💻 For Policymakers & Researchers

This project supports the development of:
- **Evidence-based, climate-smart strategies**
- **Health-inclusive agricultural policies**
- **Integrated responses** to climate-induced food insecurity



---

## 💻 Repository Layout

```text
├── data/              # Cleaned and processed datasets (from GHS-Panel)
├── models/            # R scripts and notebooks for OLS & logistic regression
├── visualizations/    # All charts, plots, and visual outputs
├── report/            # Final project write-up (PDF)
└── README.md          # Project summary and documentation


