
## PROJECT TITLE; Customer Segmentation For a Subscription Service.
---
- [Project Overview](#project-overview)
- [Data Collected](#data-collected)
- [Project Objectives](#project-objectives)
- [Tools Used](#tools-used)
- [Exploratory Data Analysis/ Data Analysis](#exploratory-data-analysis/-data-analysis)
- [Visual Analysis and Inference](#visual-analysis-and-inference)

### PROJECT OVERVIEW
---
This project collects and analyses data from various regions. The goal is to provide clarity on customer behavior, to track subscription types and identify key trends in cancellations and renewls.

### Data Collected.
---
The data collected includes the following key columns;
 - Region; The geograhpical location the store.
 - Customer Name; Names of customers that patronize each store.
 - Subscription type; Subscription type selected by each customers
 - Subscription Start; The starting date of each subscription
 - Subscription End; The date each subscription ends
 - Revenue; The total monetary value generated from sales.

### Project Objectives
---
This project was designed to address the following analysis goals;
 1. The most popular subscription type
 2. Average subscription duration
 3. Customers who canceled their subscription
 4. Customers with subscription longer than 12months
 5. Total revenue by subscription type
 6. Top 3 Region by subscription cancellation
 7. Total number of active and canceled subscription

 ### Tools Used
 ---
 - Microsoft Excel [DownHere](https://www.microsoft.come)
   1. For data cleaning
   2. For data analysis
   3. For data visualization.
 - SQL; Structured Query Language [DownloadHere](https://www.microsoft.com)
    For querying data
- Power BI (DownloadHere)[https://www.microsoft.com]
   1. For visualizing key customer segments
   2. cancellation trends
   3. For subscription trends

### Data Cleaning And Preparation
---
In the initial phase of data cleaning and preparation, the following actions were performed;
  1. Data loading and inspection
  2. Handling missing variables
  3. Data cleaning and inspection


  ### Exploratory  Data analysis/ Data Analysis
  ---
  This involves exploring of data to answer the following questions;
   - What is the average subscriptionduration using ```=average(subscription duration```
   - Which subscription type is the most popular subscription type (using conditional column to assign figure 1 to each subscription type) ```sum(subscription type)```
   - What is the total revenue ```=sum(Revenue)```
   - Find the total number of active subscription (using conditional colunm to assign figure 1 to false else assign 0) ```=count(active subscription)```
   - Find the total number of canceled subscription (unsing conditional column to assign figure 1 to true else assign 0)
      ```=count(canceled subscription)```
  
### Visual Analysis And Inference
---




![COUNT OF SUB](https://github.com/user-attachments/assets/724816f6-7d28-4398-9192-dab5acac1d5d)




![REVENUE BY SUB](https://github.com/user-attachments/assets/6555d4e3-3ae4-41a7-8e6d-f65505453406)





![SUB DURATION](https://github.com/user-attachments/assets/cbdd1480-ee47-4994-9280-ca6dd468e720)





![TOP REGION BY SUB CANCELLATION](https://github.com/user-attachments/assets/444788e1-4454-4eca-8c80-ea42dea44ce7)





![THOSE WHO CANCELED](https://github.com/user-attachments/assets/dac8b3dd-d967-4329-9d04-ed041d52d3dd)





![TOP 3 REGIONS BY SUB CANCELLATION](https://github.com/user-attachments/assets/40e4dbfa-d83d-4c7e-b021-88fd9ec190f8)






![POWER BI CD](https://github.com/user-attachments/assets/adf95c88-dfd9-4eea-bfec-bbf426592a5a)




















