 # Road Accident Dashboard
![Screenshot (74)](https://github.com/Ikumoluyi-Taiwo/Excel-Projects/assets/139241043/6693ffb3-bedf-4aec-ac3f-af14133af63c)

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
  
  Relationship between casualties by Area/Location and by Day/Night.

### Stakeholders 
  Organisations and Departments making use of this dashboard are:
  Ministry of Transport, Road Transport Department, Police Force, Emergency Services Department, Road Safety Corps, Transport Operators, Traffic Management Agencies,     Public, Media.
  
## Dataset. 
There is a raw Excel dataset provided with over 307,000 rows and 23 Columns.

## Skills Shown.
Data cleaning on this data set was minimal however, data processing and transformation skills like using formulas and building some customised columns with those formulas were carried out. During Analysis, the data was aggregated using Pivot tables and charts were created simultaneously off those aggregaions (Pivot Tables) which allowed for visualization of the data. Custom charts were created and formatting applied where necessary for the final dashboard which is dynamic.

## Transformation.
First off, the data was inspected to make sure there were no blanks or missing values in the primary key field, typographical errors and duplictes. In this dataset duplicates were removed and a typo which was corrected as seen in this case: 
### In the Accident Severity column, 'Fatal' was misspelled as 'Fetal'
![Screenshot (54)](https://github.com/Ikumoluyi-Taiwo/Excel-Projects/assets/139241043/66b4074d-65e7-41b0-8a7f-d69ca96570ee)

### This was corrected using Find and Replace.
![Screenshot (55)](https://github.com/Ikumoluyi-Taiwo/Excel-Projects/assets/139241043/4b5b19e0-86ec-402b-861d-476a66b32bcb)

### In order for comparison of the current and previous year casualties to be calculated, the month name and year was extracted from a short date format in the Accident Date column:
![Screenshot (58)](https://github.com/Ikumoluyi-Taiwo/Excel-Projects/assets/139241043/ea624059-3950-4a18-ae4a-611cea10314d)

### Into a new 'Month' and 'Year' column using the 'TEXT' function.
![Screenshot (60)](https://github.com/Ikumoluyi-Taiwo/Excel-Projects/assets/139241043/58ba3a39-6593-45f6-a04c-dbf85c9121d4)

## Analysis and Visualization.
Pivot tables were used to aggregate all the necessary KPIs and thier respective visualisations were derived off the pivot tables.

### Total Casualties
![Screenshot (72)](https://github.com/Ikumoluyi-Taiwo/Excel-Projects/assets/139241043/ab53c6cf-a982-4748-8152-12b8d07048e0)

### Total casualties and percentage of total with respect to accident severity and maximum casualties by type of vehicle.
Each level of accident severity was divided by the total of all accident severities to arrive at the death totals and percentage by accident severity:
![Screenshot (61)](https://github.com/Ikumoluyi-Taiwo/Excel-Projects/assets/139241043/c477c9fa-3778-466f-9308-e4359c286daf)

### Total % by Fatal Casualties
![Screenshot (70)](https://github.com/Ikumoluyi-Taiwo/Excel-Projects/assets/139241043/20a058c3-1284-47e9-82b8-325b386462b0)

### Total % by Slight Casualties
![Screenshot (69)](https://github.com/Ikumoluyi-Taiwo/Excel-Projects/assets/139241043/78c1afa6-1007-4ba0-b001-d64be1713095)

### Total % by Serious Casualties
![Screenshot (67)](https://github.com/Ikumoluyi-Taiwo/Excel-Projects/assets/139241043/fc507dcd-0c4c-4ef4-b20e-f3cdb3586208)

### Maximum casualties by type of vehicle.
The total of car casualties was divided by the total of all other vehicle types:
![Screenshot (71)](https://github.com/Ikumoluyi-Taiwo/Excel-Projects/assets/139241043/ff23091f-5ea2-4caa-8db3-face5bd2f653)
![Screenshot (73)](https://github.com/Ikumoluyi-Taiwo/Excel-Projects/assets/139241043/516f25b0-f8ad-4b7b-9f05-d43d143d534a)

### Monthly trend showing comparison of casualties for current year and previous year.
The month and year values were extracted from the pivot tables into a new table to for use in a line chart:
![Screenshot (75)](https://github.com/Ikumoluyi-Taiwo/Excel-Projects/assets/139241043/7a9fe696-1f7f-40cf-bc45-7606124058b5)

### Monthly trend of Current year vs Previous year casualties
![Screenshot (76)](https://github.com/Ikumoluyi-Taiwo/Excel-Projects/assets/139241043/38af05a9-29ce-4071-b986-1fb3b301ed75)

### Maximum casualties by Road Type.
![Screenshot (78)](https://github.com/Ikumoluyi-Taiwo/Excel-Projects/assets/139241043/21c89ffd-7e4b-456d-bb4b-7004beaeae8e)

### Distribution of total casualties by Road Surface.
The road surface and casualties values were extracted from the pivot tables into a new table to for use in a treemap:
![Screenshot (79)](https://github.com/Ikumoluyi-Taiwo/Excel-Projects/assets/139241043/ff805a31-d36d-497b-9582-c71184425474)

### Relationship between casualties by Area/Location and by Day/Night.
![Screenshot (81)](https://github.com/Ikumoluyi-Taiwo/Excel-Projects/assets/139241043/8f32ca5c-92f9-46ff-ae7d-cb82c97dd849)

## Conclusion.
The original dataset was preserved and all data processes transformations were carried out a working sheet. This is advisable incase there is a need for the raw dataset or in the event of an error/mistakes during data analysis stage. 
A data analysis sheet was also created with all the KPI used in the entire analytical process in order to allow the stakeholders, or even a new developer to easily identify the aggregations used to build the necessary pivot tables used in analysing the dataset.
With all that being done, the request from the stakeholders was fulfilled, and a report addressing their demands produced. 
