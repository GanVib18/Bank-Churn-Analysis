# Churn-Analysis-Power-BI

Customer churn is one of the biggest expenditures of any organization. An analysis of churn would immensely help any organization to strategize their retention initiatives. Churn prevention allows companies to develop loyalty programs and retention campaigns to keep as many customers as possible.

The following is a project analyzing a bank's churn over the course of 4 years (2016 to 2019). Data was gathered in a Data Warehouse in Microsoft Azure (Synapse Analytics) where a connection was established with MySQL Workbench. Rudimentary data cleaning was performed - Removal of Undesired and missing entries, Dealing with Type mismatch, and Correcting date formats. Next step in the ETL was to connect Microsoft Azure with Power BI. Data modelling was conducted using star schema. To optimize the model I turned off Time Intelligence and used the Power Query to remove any rows/columns I did not require. Data was further transformed by using Data Analysis Expressions (DAX). Measures were created in the calculations entity to better present and understand the relationships between different churn features. Then UI was enhanced and interactive visualizations were created on a Power BI report. The project was then loaded into a Power BI workspace where the report was finalized and a static dashboard was created. A Power BI gateway was created and daily refreshes were scheduled for the data. Finally, the reports and dashboards were loaded onto an app which was then tested before deploying. 

Project Flow Steps: 

1. Business requirement document (BRD) 
2. Data Gathering 
3. Data cleaning and transformation 
4. Data modelling 
5. UI 
6. DAX Functions 
7. Enhance UI 
8. RLS 
9. Create and provide the workspace access 
10. Publish the report to the workspace 
11. Build Dashboard and Mobile view 
12. Establish Gateway  
13. Schedule daily refresh 
14. Add roles to security 
15. Subscribe and manage alerts 
16. Create and deploy as an app

Technologies: Microsoft Azure, Power BI

DataBase: MySQL 
