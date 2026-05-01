# 🌍 Life Expectancy Dataset Analysis

## 📌 Project Overview

This project explores the **Life Expectancy Dataset** to understand which social, economic, health, and development-related factors are associated with life expectancy across countries.

The main goal is to analyze how predictors such as GDP, adult mortality, immunization rates, schooling, BMI, and country development status relate to life expectancy.

---

## 📊 Dataset Description

Life Expectancy Dataset:  Total 2938 observations (country-year rows) and 22 columns (including 1 response variable and 21 predictor variables).  It covers total 193 countries, 2000–2015.   

Country: Country under study  
Year: year  
Status: Status of the country's development  
Population: Population of country  
Adult mortality: how many adults die before reaching age 60 per 1000 population  
Hepatitis B: Percentage of people finally one year old who were immunized against hepatitis B  
Measles: The number of reported measles cases per 1000 people  
Polio: Percentage of 1-year-olds immunized against polio  
Diphtheria: Percentage of people finally one year old who were immunized against diphtheria  
HIV/AIDS: The number of deaths caused by AIDS of the last 4-year-olds who were born alive per 1000 people  
infant deaths: The number of infant deaths per 1000 people  
under-five deaths: The number of deaths of people under 5 years old per 1000 people  
Percentage of Expenditure: The percentage of a country’s total government spending that is spent on healthcare.  
Total expenditure: The ratio of government medical-health expenses to total government expenses in percentage  
Income composition of resources: how much income contributes to a country’s overall human development, especially in terms of living standards  
GDP: Gross domestic product  
BMI: The average body mass index of the entire population of the country  
Thinness 1-19 years: Prevalence of thinness among people 19 years old in percentage  
Thinness 5–9 years: The percentage of children aged 5 to 9 who are underweight  
Alcohol: Liters of alcohol consumption among people over 15 years old  
Schooling: The number of years that people study  
Life expectancy: Country life expectancy  

Response variable (Y) is Life expectancy.  

---

## Research Questions

Which variables are useful in explaining life expectancy?


---

## 🎯 Research Objective

The objective of this project is to examine relationships between life expectancy and multiple predictors using statistical modeling and data visualization.

This project may include:

- Exploratory Data Analysis  
- Data cleaning and missing value handling  
- Visual comparison between developed and developing countries  
- Multiple linear regression modeling  
- Model diagnostics  
- Interpretation of significant predictors  

---

## 🧪 Methods

The analysis may use the following methods:

- Summary statistics  
- Correlation analysis  
- Scatterplots and boxplots  
- Multiple linear regression  
- Interaction terms  
- Model comparison  
- Residual diagnostics  

---

## 📁 Suggested Repository Structure

```text
life-expectancy-analysis/
│
├── README.md
├── data/
│   └── Life_Expectancy_Data.csv
│
├── scripts/
│   └── analysis.R
│
├── reports/
│   └── life_expectancy_report.qmd
│
├── figures/
│   └── plots/
│
└── output/
    └── model_results/
