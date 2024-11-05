# LITA_CAPSTONE_PROJECT
This is where you find the documentation of my Capstone Project with the Incubator Hub.  
### Project Title: Customer Segmentation for Subscription Service

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Project Objectives](#project-objectives)

[Tools and Methods Used](#tools-and-methods-used)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Formula Used](#formula-used)

[Data usage](#data-usage)

[Dashboard Overview](#dashboard-overview)


### Project Overview
---
This project involves analysing customer data for a subscription service to identify segments and trends. The goal is to
understand customer behaviour, track subscription types and identify key trends in cancellations and renewals

### Data Source
---
The primary source of the Data used here was received from LITA_The_Incubator_Hub 
LMS which I downloaded into my System for the analysis. It is an Excel File
Find link to file here:
https://canvas.instructure.com/courses/10186984/files/folder/Portfolio%20Building%20with%20GitHub%20and%20Introduction%20to%20Power%20BI

The dataset include the following columns:

1. CustomerID: The identity of each customer
2. CustomerName: Name of each customer
3. Region: Geographical location of Subcribers
4. Subscription Type: Subscription packages
5. Subscription Start: Begining of Subscription
6. Subscription End: Termination of Subscription
7. Cancelled: Active & Cancelled subcribers
8. Revenue: Amount generated by Service Provider.  

### Project Objectives
 ---
This project was designed to analyze and report with an interactive POWER BI dashboard the following findings:

  -Customer by subscription type: This aim at knowing the number of subscriber and the type of package they belong
 
  -Total Reveue: this represent the total sales made by the servive provider within the year included in the dataset  
               
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

  - Calculation of subscription duration
  - Number of subscriber from each region.
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
---
 

![LITA PROJECT CUST  DASHBOARD](https://github.com/user-attachments/assets/8420f504-487e-43d6-8a8a-dbbbeaddbd7b)


### Data Analysis and Insights Generation:

### Insights

- Subscription Type, Region and Cancellation: At about 17k subscribers, the basic subscription type has the highest
   subscribers making it the preferred subscription type. The premium and standard subscription type have similar
   customer base at 8446 and 8420 respectively. The North, South and West are the regions with cancellation.
   The South has the highest with 8446 followed by the North at 8433 and lastly the West with 8420.
   The East and North Region have Basic Subscribers, the South have Premium Subscriberswhile the West
   have Standard Subscribers.


   
![LITA PBI PROJECT  2 png](https://github.com/user-attachments/assets/30edd1d9-3fac-4ea9-875d-609b0943255d)


### Insight:
  - Revenue and Region: From the report a total revenue of 67.5M was generated by the four regions which represent 
    the geographical location of subcribers with the North and East making up the contributors of the highest revenue
    (Subscription type- Basic) with the Average subscription duration of 12 months.




  ![LITA PBI PROJECT  3 png](https://github.com/user-attachments/assets/042e8d93-05c9-459a-930e-885d5a753f7b)



### Recommendations

- Since the preferred subscription type is the Basic type, it only suggest that customers are more inclined
  potentially due to lowest cost or entry-level features that meets their needs.




- The three regions have almost equal cancellation rates, each approximately one-third of the total cancellations
  This suggests that cancellation is evenly distributed across these regions and does not seem to be significantly
  affected by geographical differences.   

  
