# **🌍 World Suicide Mortality Analysis (2001–2021)**

## **Table of Content**
1. [INTRO](#-introduction)
1. [OBJECTIVE](#-objectives)
1. [DATA SOURCE](#-data-source)
1. [KEY FINDINGS](#-key-findings)
1. [CONCLUSION](#-conclusion)

### **📘 Introduction**

This project explores global suicide mortality trends between 2001 and 2021 using publicly available datasets.
The goal is to understand how suicide rates vary across countries, identify high-risk regions, and observe how patterns changed during significant global events such as the COVID-19 pandemic.

Using Python (Pandas), the analysis examines data quality, computes country-level statistics, and extracts insights relevant for public health, mental health advocacy, and global policy research.

---

### **🎯 Objectives**

The main objectives of this analysis are:
1. Assess Data Quality
    - Check for duplicate entries
    - Identify missing values

2. Country-Level Analysis
    - Determine the number of countries represented
    - Find each country's highest recorded suicide mortality rate
    -Identify the country with the overall highest suicide rate

3. Trend Analysis
    - Determine Nigeria's highest suicide rate and the year it occurred
    - Compare suicide rates of Nigeria and Niger for specific years
    - Identify which country had the highest suicide mortality rate during the COVID-19 year (2020)

4. Threshold-Based Insights
    - Count how many countries recorded suicide rates greater than 20 between 2005 and 2010

---

### 📂 **Data Source**

This data was download from [Kaggle](kaggle.com)\
Columns included:`Country Name`,`Country Code`,`Year`,`Suicide Rate`

---

### **🔍 Key Findings**

> 1. Data Quality

    Duplicates found: 1,892 rows

    Missing values: 0 (dataset is complete)

> 2. Nigeria's Suicide Rate

    Nigeria's highest recorded suicide mortality rate occurred in 2001

    Highest value: 5.37

> 3. Countries Represented

    Total number of unique countries: 233

> 4. Highest Suicide Rate (Global)

    Country: Russian Federation

    Year: 2001

    Rate: 51.79 (highest in the entire dataset)

> 5. Nigeria vs Niger (2015)

    Nigeria 2015: 4.46

    Niger 2015: No available data

    (Nigeria recorded the higher rate for that year among the two as no 2015 data for Niger.)

> 6. COVID-19 Year Analysis (2020)

    Country with highest suicide mortality rate: Suriname – 28.47

> 7. Highest Mortality Rate by Country

    A full table was generated showing each country's maximum suicide rate between 2001–2021.

> 8. Countries with Suicide Rate > 20 (2005–2010)

    Number of countries that exceeded the threshold: 23


---

### **📌 Conclusion**

This analysis provides a clear overview of suicide mortality patterns across the globe, highlighting regional disparities and notable periods such as the COVID-19 pandemic.
The dataset is clean, comprehensive, and reveals significant differences in suicide risk across countries, which can guide further research into mental health trends and contributing socio-economic factors.
