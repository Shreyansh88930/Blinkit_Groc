**Blinkit Sales Performance Dashboard**
View the Live Interactive Dashboard Here
<img width="1138" height="610" alt="Screenshot 2025-08-24 163221" src="https://github.com/user-attachments/assets/c39494f0-8fbd-462a-9081-b039d99e9fdf" />



This project presents a comprehensive sales performance analysis for Blinkit, an Indian last-minute delivery service. The goal of this Business Intelligence project is to provide actionable insights into Blinkit's sales across various dimensions, including outlet characteristics, product details, and historical trends. The dashboard is built entirely in Microsoft Power BI.

**Problem Statement**
The primary objective is to answer key business questions that can help drive strategic decisions. These include:

A) What are the primary drivers of sales performance?
B) Which product categories, outlet types, and geographical locations are the most profitable?
C) How have sales trended over the years, and are there any noticeable patterns?
D) What is the relationship between product attributes (like fat content) and sales volume?

**Tools & Technologies**
Primary Tool: Microsoft Power BI

**Components Used:**

Power Query: For Extracting, Transforming, and Loading (ETL) the data.

Data Modeling: To create a robust star schema with well-defined relationships.

DAX (Data Analysis Expressions): For creating custom measures and calculated columns.

**Data Preparation & Modeling**
The process began with connecting to the raw sales data. Using Power Query, the following data preparation steps were performed:

Data Cleaning: Handled missing values, removed duplicates, and corrected data type inconsistencies.

Data Transformation: Created new columns (e.g., categorizing sales tiers) and structured the data for optimal analysis.

Data Modeling: Established relationships between the fact table (Sales) and dimension tables (Outlets, Products, Time) to create an efficient star schema. This model serves as the foundation for all visualizations and calculations.

**Key Metrics & KPIs**
The dashboard focuses on the following Key Performance Indicators (KPIs):

Total Sales: $1.20M

Average Sales: $141

Total Number of Items Sold: 8,523

Average Customer Rating: 3.9

**Key Insights & Findings**
The analysis revealed several actionable insights:

Top Performing Outlets: "Supermarket Type 2" outlets are the highest revenue generators, contributing approximately $788K to total sales, indicating a successful store format.

Geographical Strength: Tier 3 city locations account for the highest sales volume, suggesting strong market penetration and customer demand in those areas.

Product Trends: "Fruits and Vegetables" is the top-selling product category, highlighting its importance to the overall business.

Historical Sales Performance: The company experienced peak sales around 2018-2019, with a slight decline in subsequent years. This trend warrants further investigation to understand the underlying causes and formulate a strategy for growth.

Consumer Preferences: Products with "Regular Fat Content" significantly outsell "Low Fat" options, pointing to specific consumer purchasing habits that can inform marketing and inventory decisions.

**Dashboard Features**
Interactive Filters: Dynamic slicers for Outlet Location Tier, Outlet Size, and Item Type allow users to drill down into specific segments.

Cross-Filtering: All visuals are interconnected, enabling users to click on any element to filter the entire report.

Comprehensive Visuals: The dashboard includes a mix of visuals like area charts, bar charts, donut charts, and a detailed matrix to provide a holistic view of the business.

**How to Use This Repository**
View the Live Dashboard: The best way to experience the project is through the interactive version linked at the top of this README.

Explore the Power BI File: The .pbix file is included in this repository. You can download it and open it with Power BI Desktop to explore the data model, Power Query transformations, and DAX measures used.
