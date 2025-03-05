# Sales Data Exploration and Dashboard

In today's fast-paced business environment, the need for accessible, reliable sales data is critical for informed decision-making. The Sales Data Exploration and Dashboard project aims to provide a comprehensive analysis and visualization platform for understanding sales performance and trends. Leveraging datasets from various sources, the project utilized SQL data exploration techniques to extract insights and develop a Tableau dashboard. By offering stakeholders a user-friendly interface to explore key metrics such as sales revenue, profit, and customer demographics, the project empowers data-driven decision-making and fosters strategic planning.

## Access the live dashboard on Tableau Public
[Sales Dashboard](https://public.tableau.com/app/profile/ramyadevipriya.yogeeswaran/viz/PortfolioProject01_17341122603910/SalesDashboard)
![Screenshot 2025-03-05 130832](https://github.com/user-attachments/assets/8f6e6965-7acf-4edc-8452-12f9298f7366)

## Project Overview
This document serves as documentation for the Sales Data Exploration and Dashboard project, which aimed to analyze and visualize sales-related data. The project involved SQL data exploration, table creation, data cleaning, and the development of a comprehensive dashboard using Tableau.

## Project Scope
The project utilized sales data from various sources, focusing on metrics such as sales revenue, profit, customer demographics, and product performance. The data exploration phase involved SQL queries to extract, clean, and transform the dataset for analysis. Subsequently, a Tableau dashboard was developed to visualize key insights and trends.

## Tools and Technologies
The project utilized the following tools and technologies:
- **SQL (Structured Query Language):** The primary language used for data manipulation, exploration, and analysis.
- **SQL Server Management Studio (SSMS):** For database creation, data parsing, and initial data exploration.
- **Tableau:** For creating a variety of visualizations and interactive dashboards based on SQL query findings.
- **Excel:** The initial file type for data exploration, as the dataset obtained was in Excel format.

This combination of tools facilitated a comprehensive approach to the analysis, from database creation and exploration using SQL to visual representation and interactive dashboards in Tableau. The dataset's initial format in Excel underscored the importance of diverse tools in handling and extracting insights from real-world datasets.

## Data Exploration
The sales dataset contained various metrics such as sales revenue, profit, customer demographics, and product performance. The data exploration phase involved two main SQL scripts executed on SQL Server: `table_creation.sql` and `data_exploration.sql`.

### `table_creation.sql`
This script focuses on creating tables and performing initial data processing steps to prepare the dataset for analysis. It includes the following tasks:
- Specifying the specific database name
- Creating tables from the raw dataset
- Retrieving column data types and correcting them as necessary for easier data exploration

### `data_exploration.sql`
This script consists of steps taken after the initial table creation, focusing on extracting relevant data for exploratory data analysis. It includes the following tasks:
- Selecting relevant data for analysis, including metrics such as sales revenue, profit, and customer demographics
- Finding potential Key Performance Indicators (KPIs) such as total sales, total profit, and customer acquisition
- Conducting comparative analysis:
  - Comparing sales performance across different regions
  - Sorting products by highest sales and profit margins
  - Calculating metrics like average order value and customer lifetime value

These SQL scripts were crucial in preparing and exploring the sales dataset, providing the necessary foundation for subsequent analysis and visualization.

## Tableau Dashboard
Access the live dashboard on Tableau Public: [Sales Dashboard](https://public.tableau.com/app/profile/ramyadevipriya.yogeeswaran/viz/PortfolioProject01_17341122603910/SalesDashboard)

The Tableau dashboard was designed to visualize key insights and trends related to sales performance, including total sales, profit, customer demographics, and product performance. The dashboard includes KPIs, text charts, symbol maps, and area graphs to provide a comprehensive overview of sales data.

### Dashboard Components:
- **Key Performance Indicators (KPIs):**
  - Total sales revenue
  - Total profit
  - Customer acquisition
- **Text Chart:**
  - Sales and profit by product/category
- **Symbol Map:**
  - Sales distribution by region
- **Area Graphs:**
  - Sales revenue over time by region
  - Profit over time by region
  - Customer acquisition over time

## Project Conclusion
The Sales Data Exploration and Dashboard project has provided invaluable insights into sales performance through meticulous data analysis and visualization. By leveraging SQL queries and Tableau's visualization capabilities, the project distilled complex sales datasets into actionable insights accessible to a broad audience. The interactive Tableau dashboard serves as a centralized platform for tracking key metrics and empowering stakeholders to make informed decisions. Moving forward, these insights will continue to inform business strategies and shape sales planning, highlighting the project's lasting impact on data-driven decision-making in the business world.

## Recommendations and Future Work
- Continuously update the dashboard with the latest sales data.
- Enhance interactivity and user experience by adding more filters and drill-down options.
- Conduct further analysis to identify correlations and causal relationships between variables.

## Files Included
- `Sales_Dashboard.twbx`: This file is the Tableau packaged workbook that contains all the visuals, dashboards, and supporting local file data and background images.
- `Sales Dashboard by [Your Name].png`: A still image of the interactive dashboard created on Tableau Desktop.
- `table_creation.sql`: This file provides SQL queries tailored for table creation on SQL Server.
- `data_exploration.sql`: This file provides SQL queries tailored for data exploration.
- `README.md`: This file provides an overview of the project.

