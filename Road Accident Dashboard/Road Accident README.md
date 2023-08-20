 # Road Accident Dashboard

## About The Project.
This is a manipulated and made up dataset from Kaggle that reports road casualties in a particular location.

## Project Requirement.
The client wants to create a road accident dashboard for the years 2021 and 2022 so as to have some insights on the below requirements:
### Primary KPI Total casualties taken place after the accident.

### Primary KPIs Total casualties and percentage of total with respect to accident severity and maximum casualties by type of vehicle.

### Secondary KPIs
  Total casualties with respect to vehicle type.
  Monthly trend showing comparison of casualties for current year and previous year.
  Maximum casualties by Road Type.
  Distribution of total casualties by Road Surface.
  Relation between casualties by Area/Location and by Day/Night.

### Stakeholders 
  Organisations and Departments making use of this dashboard are:
  Ministry of Transport, Road Transport Department, Police Force, Emergency Services Department, Road Safety Corps, Transport Operators, Traffic Management Agencies,     Public, Media.
  
## Dataset. 
There is a raw Excel dataset provided with over 307,000 rows and 23 Columns.

## Skills Shown.
Data cleaning on this data set was minimal however, data processing and transformation skills like using formulas and building some customised columns with those formulas were carried out. During Analysis, the data was aggregated using Pivot tables and charts were created off those aggregaions which allowed for visualization of the data. Custom charts were created and formatting applied where necessary for the final dashboard which is dynamic.

## Transformation.
First off, the data was inspected to make sure there were no blanks or missing values in the primary key field, typographical errors and duplictes. In this dataset duplicates were removed and a typo which was corrected as seen in this case: 
In the Accident Severity column, 'Fatal' was misspelled as 'Fetal'


The Target Tables contain information/records of Yearly/Monthly Product Targets (Volume) assigned to each Sales representative, identified by the SalesRepID. This table was duplicated four times for each distinct year (e.g., 2022, 2023, 2024, and 2025) separately. Subsequently, the corresponding tables were appended to form a new table, consolidating the previously separate yearly Target columns. The columns were edited and renamed based on the information they contain.
The Target Table was then merged with the DimProducts Table using the Primary/Foreign Key relationship of the ProductID column in both tables to retrieve the Product Price. This is important in order to calculate the budgeted Target Revenue. The Month and Year columns were duplicated, and the duplicated columns were then merged to form a Date column. Furthermore, the Sales 2022 and Sales 2023-2025 tables were appended to create a new Sales Table that has all Sales records from years 2022 to 2025 which was then merged with the DimProducts Table using the Primary/Foreign key relationship of the ProductID Column in both Tables to get the Product Price.This is crucial in order to calculate the Actual Revenue.


## Analysis.
1. The Sales Representative can track their performances through-out the periods to plan their marketing activities.
2. The Team Managers can track their teams' performances through-out the periods to plan their teams' activities.
3. Executive team can track Revenue numbers to monitor alignment with the set targets to influence medium to long term strategies.

## Sales Performance Overview.
1. Total  Revenue
2. Total Revenue Year To Date (YTD)
3. Total Revenue Previous Year YTD
4. Total Revenue Same Period Last Year(SPLY)
5. Total Target
6. Total TargetYTD
7. Actual Revenue Performance Previous Year YTD vs Target Previous Year YTD
8. Actual Revenue Performance YTD vs Target YTD
9. Revenue Month on Month Percentage Change
10. Revenue Distribution by Location
11. Revenue by Channel
12. Revenue by Product Class

![Sales Report 1](https://github.com/Ikumoluyi-Taiwo/PortfolioProjects/assets/139241043/bb5c4cea-ef6e-4d0f-9d2c-a59b76e4d3f1)
![Sales Report 2](https://github.com/Ikumoluyi-Taiwo/PortfolioProjects/assets/139241043/ffe6775b-0fa2-4568-8ce1-73aaf3132432)

## Marketing Performance.
1. Revenue Achieved vs Revenue Target
2. Volume Achieved vs Volume Target
3. Actual Revenue by Sales Representative
4. Target Revenue Achievement% by Sales Representative
5. Actual Volume by Sales Representative
6. Target Volume Achievement by Sales Representative
7. Actual Revenue Achievement by Sales Team
8. Revenue and Volume Achievement by Product.

![Marketing Performance 1](https://github.com/Ikumoluyi-Taiwo/PortfolioProjects/assets/139241043/418b3eab-5631-4bb8-a50e-241e351b45d7)
![Marketing Performance 2](https://github.com/Ikumoluyi-Taiwo/PortfolioProjects/assets/139241043/33e462b0-8480-4062-9524-8a522dce951e)

## Report.
You can find the full report of this Analysis here: https://app.powerbi.com/reportEmbed?reportId=73496be3-742d-4bc4-b8dd-6f60f7f80607&autoAuth=true&ctid=c1b84f64-1fcc-4038-a4fa-2bfdda89f208

## Conclusion.
The request from the stakeholders was fulfilled, and a report addressing their demands produced. 
