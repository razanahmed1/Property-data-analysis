# 📊Analysis of the Number of Establishments in Saudi Arabia in 2023

## 📌About the Project
This project initiated an interactive dashboard to analyze the number of establishments in Saudi Arabia for 2023, after testing the data using an Excel stock analysis model in Power PI. The dashboard highlights key elements by size, region, and quarter, with interactive filters for economic activity and geographic location.

## 🎯 Objective 

The objective of this project is to provide clear insights into the distribution of establishments and beneficiaries
By preparing and modeling the data in Power BI, the project aims to:

* Highlight the total number of establishments per category
* Compare beneficiaries by gender and disability status
* Organize data by year and quarter for better analysis
* Deliver an interactive dashboard that supports decision-making
  
## 🔍Project Features
Display of Key Performance Indicators (KPIs)
* Total Establishments
* Large Establishments
* Medium Establishments
* Small Establishments
* Micro Establishments
* Regional distribution of establishments across Saudi Arabia
* Quarterly comparison for the year 2023
* Interactive slicers for economic activity and region
* A visual chart showing total establishments per quarter by region
  
## 🛠️Tools Used
- Excel
- Power Bi
- Power Query
- Dax
## 🧹 Data Preparation (Power Query)

* Changed data types.
* Cleaned null values.
* Renamed fields.
* Added a new column “Total Establishments” to calculate the overall number of establishments per category
* Created a helper table for quarters (1, 2, 3, 4 – First, Second, Third, Fourth)

## 🧩 Data Modeling (Model View)

* The model includes two tables:Table1: the main table containing establishments and beneficiaries data
* Quarter Table: a helper table containing numeric and text values for quarters
* A relationship was created between the two tables in Model View to ensure logical ordering of quarters in visuals and filters

  ## 🗂️ Data Structure

#### Establishments Columns

* Total Establishments: added column to calculate the overall number of establishments per category
* Category: type of category or classification
* Year: the year of the data

#### Beneficiaries Columns

* Total Beneficiaries: overall number of beneficiaries
* Male Beneficiaries: number of male beneficiaries
* Female Beneficiaries: number of female beneficiaries
* Beneficiaries with Disabilities: number of beneficiaries with disabilities
* Beneficiaries without Disabilities: number of beneficiaries without disabilities

  ## 🖼️ imaage Project
  
  ![image here]()
  
## 📁 Files 

-  contains raw data, analysis, and charts
  -  

## 🚀 Future Improvements

* Add year-over-year comparisons
* Calculate growth rates
* Enhance dashboard design and expand filter options.
