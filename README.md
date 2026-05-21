# 📱 Mobile Sales Data Analysis

This project analyzes mobile sales data to uncover insights on customer behavior, product demand, pricing, and regional performance for better data-driven decision-making.

## 📌 Overview  
This project focuses on analyzing mobile sales transaction data to understand how different factors such as customer behavior, product demand, pricing categories, and regional performance impact overall business sales. Using Power BI, raw transactional data was transformed into an interactive reporting solution that provides a clear view of business performance through KPIs, trends, and visual analysis. The report consists of four dashboards covering sales overview, customer insights, product performance, and regional analysis. Together, these dashboards help uncover meaningful patterns in sales data and support better business decision-making through interactive and easy-to-understand visualizations.

## 📌 Problem Statement  
The business was generating large volumes of sales data across multiple brands, cities, customer groups, and payment methods. However, the data was scattered and difficult to analyze efficiently using raw records alone. As a result, management lacked clear visibility into sales performance, customer preferences, regional trends, and underperforming areas affecting business growth. Without a structured reporting system, identifying changing market trends and making timely business decisions became increasingly challenging.

## 📌 Project Objective  
The objective of this project was to build an interactive analytical solution that could transform raw sales data into actionable business insights. The project aimed to:  
- Monitor overall sales performance through key KPIs  
- Analyze customer purchasing behavior and product demand  
- Identify top-performing brands, cities, and customer segments  
- Track monthly and regional sales trends  
- Support data-driven decision-making through interactive dashboards  

## 📂 Dataset Information  
The dataset used in this project contains approximately 3,800 mobile sales transactions. The data was imported from an Excel file and includes detailed information related to:  
- Transaction ID  
- Date Information (Day, Month, Year, Day Name)  
- Mobile Brand and Model  
- Units Sold  
- Price Per Unit  
- Customer Name and Age  
- City  
- Payment Method  
- Customer Ratings  

## 📌 Data Preparation & Modeling  
- Standardized column names, formats, and data types to ensure consistency and accurate analysis  
- Created dimension tables including Dim_Product, Dim_Customer, Dim_Payment, and Dim_Calendar in Power Query to improve scalability and support organized reporting  
- Developed a dynamic Dim_Calendar table in Power Query using M language to support time intelligence calculations and trend analysis  
- Implemented a star schema data model by establishing relationships between fact and dimension tables  
- Performed data modeling, transformation, and analytical processes within Power BI  
- Created calculated columns and DAX measures for KPIs, customer segmentation, city tiers, and pricing categories used across the dashboards  

## 🛠️ Tech Stack  
- Power BI Desktop – Dashboard development and visualization  
- Power Query – Data cleaning and transformation  
- DAX – KPI calculations and analytical measures  
- Data Modeling – Star schema modeling and relationship management  
- Microsoft Excel – Data source  
- Git & GitHub – Version control and project publishing  

## 👤 Author  
Sapna Devi