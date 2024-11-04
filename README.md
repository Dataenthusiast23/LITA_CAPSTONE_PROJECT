# LITA_CAPSTONE_PROJECT
Customer Data - This is where you find the documentation of my Capstone Project with the Incubator Hub.  
### Project Title: Customer Segmentation for Suscriptipon Service

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Project Objectives](#project-objectives)

[Tools and Methods Used](#tools-dnd-methods-used)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Formula Used](#formula-used)

[Data usage](#data-usage)

[Dashboard Overview](#dashboard-overview)


### Project Overview
---
This project involves analysing customer data for a subscription service to identify segments and trends.The goal is to
understand customer behaviour, track subscription types and identify key trends in cancellations and renewals

### Data Sources
---
The primary source of the Data used here is Customer Data.xlsx. which I received from my school 
LMS which I downloaded into my System for the analysis. The dataset include the following columns:

1. OrderID
2. CustomerID
3. Product
4. Region
5. OrderDate
6. Quantity
7. Unit Price
   
### Project Objectives
 ---
This project was designed to analyze and report with an interactive POWER BI dashboard the following findings:

  -Customer by subscription type: This aim at knowing the number of subscriber and the type of package they belong
 
  -Total Reveue: this represent the total sales made by the servive provider within the two years included in the dataset  
               
  -Total number of cancelled subscription: this seeks to calculate the number of cancellations by subscribers.

  ### Tools and Methods Used
   ---
- Microsoft Power BI [Download Here](https://www.microsoft.com)
    
  -Data Analysis: This was achieved using power query editor for cleaning, removing duplicate, adding new columns, changed text type
      for easy interpretation. 
     
  -Data Visualisation: Visuals created in the report view  to visually represent the Key insights. 
    
  -GitHub for Portfolio Building

### Exploratory Data Analysis
---
EDA Involved the exploring of the data to answer some questions about the Data such as;

  - Number of subscriber from each reion.
  - Which category has the highest revenue?
  - What is the top Subscription type?
  
### Formula Used
---

```
  SELECT region, COUNT(CustomerName) AS totalcustomers
  FROM [dbo].[CUSTOMER RECORD 1]
  GROUP BY region;
```

### Data Usage 
---

   - Total Revenue: represents the total Sales from all subscription type and region in the dataset.

  - Top 3  region by cancellation: this gives understanding to the regions that have the highest cancellation 
    
  - Customer by subscription type: This gives insight to the types of subscription with the number of subscibers

### Dashboard Overview

 
