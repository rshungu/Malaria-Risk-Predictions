# 🦟 Malaria Risk Prediction and Spatial Analysis  
In this project, I analyze **malaria cases, mortality, and healthcare access** using the **WHO Global Malaria Report 2023 data**. 

My goal is to identify the key **risk factors**, uncover **trends**, and **predict high-risk areas** for malaria using both machine learning and GIS (Geographic Information Systems) tools.

---

## 📌 **Project Objectives**
- **Analyze malaria cases & deaths** over the years (from **2000 to 2022**).
- **Examine healthcare access & intervention coverage**,comparing the public and private sectors
- **Predict malaria risk levels** based on environmental & demographic factors.
- **Map malaria burden spatially** using GIS tools to identify areas of concern.

---

## **Datasets Used**
### **WHO Malaria Data (Annex 4F & 4G)**
| **Dataset** | **Description** | **Columns of Interest** |
|------------|----------------|-------------------------|
| **4F** - Malaria Cases & Deaths (2000-2022) | Annual malaria burden per country | Year, Country, Cases, Deaths, Population |
| **4G** - Malaria Cases by Healthcare Access (2022) | Cases reported by public/private sector | At-risk Population, Public & Private Cases |
| **4H** - Malaria Mortality by Region (2000-2022)| Annual malaria mortality rates by region | Year, Region, Mortality rate |
| **4I** - Malaria Intervention Coverage (2022) | Malaria intervention rates by region and sector | Region, Public Sector Intervention, Private Sector Intervention |
| **4J** - Malaria by Risk Factor (2022) | Data on risk factors contributing to malaria spread | Region, Risk factor, Type, Number of cases|

**Source**: [WHO World Malaria Report 2023](https://www.who.int/teams/global-malaria-programme/reports/world-malaria-report-2023)  

---

## **Tech Stack**
- **Python**: pandas, scikit-learn, matplotlib, geopandas
- **SQL**: PostgreSQL for structured queries
- **GIS Tools**: QGIS, ArcGIS, folium (Python)
- **Visualization**: Power BI, R Shiny

---

## **Next Steps**
- **Clean & preprocess datasets**
- **Perform exploratory analysis (EDA)**
- **Build machine learning models** to predict malaria risk and identify high-risk areas
