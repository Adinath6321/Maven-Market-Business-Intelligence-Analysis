# Maven-Market-Business-Intelligence-Analysis
📊 Project Overview
This project focuses on transforming raw retail data into an end-to-end Power BI business intelligence solution. The analysis tracks Key Performance Indicators (KPIs) for Maven Market, a multi-national retail corporation, across its operations in the USA, Canada, and Mexico.

The project demonstrates advanced data modeling, DAX (Data Analysis Expressions) calculations, and interactive dashboard design to monitor sales performance, return rates, and customer demographics.

🗂️ Data Architecture
The project utilizes a Star Schema configuration, connecting several lookup tables to core transaction fact tables:

Fact Tables:

. Transactions (1997 & 1998): Detailed records of every purchase.

. Returns (1997-1998): Tracking product returns and return rates.

. Dimension (Lookup) Tables:

. Customers: Demographic data (income, occupation, homeownership).

. Products: Details on pricing, cost, and brand categorization.

. Stores: Location details and store square footage.

. Regions: Sales districts and regional hierarchies.

. Calendar: Time-based dimensions for trend analysis.

🚀 Key Features & Analysis
. Data Modeling: Established a robust relational model with one-to-many relationships.

. DAX Measures: Developed complex measures for Total Revenue, Total Profit, Return Rate, and Year-to-Date (YTD) performance.

. Geospatial Mapping: Visualized sales distribution across North American territories.

. Executive Dashboard: High-level overview of store performance, top-selling brands, and monthly revenue trends.

🛠️ Tools Used
. Power BI Desktop: For data modeling and visualization.

. Power Query (M): For data cleaning and transformation.

. DAX: For advanced analytical calculations.

. CSV Datasets: Sourced from Maven Market's internal databases.

📈 Insights Captured
. Identification of high-performing store types (Supermarkets vs. Gourmet Markets).

. Correlation between customer education levels and purchasing behavior.

. Monitoring of product return spikes to optimize supply chain quality.
