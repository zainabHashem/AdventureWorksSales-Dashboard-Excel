AdventureWorks Sales Dashboard Project
Overview

This Excel project presents an interactive dashboard that visualizes sales data from the AdventureWorks2019 database. The dashboard helps analyze the total sales, sales by category, and sales by territory over time. Key metrics like total sales, running totals, and monthly differences are calculated to provide deeper insights into the sales trends.
Main Features:

    Sales by Category: A pie chart showing the distribution of sales across different product categories (Accessories, Bikes, Clothing, and Components).

    Number of Orders by Category: A horizontal bar chart visualizing the number of orders placed for each product category.

    Total Sales by Month: A line chart depicting monthly sales trends throughout the year.

    Running Total & Monthly Difference: A table showing monthly total sales, cumulative running sales, and the difference in sales from the previous month.

    Total Sales by Territory: A bar chart representing sales across different geographical regions, such as Australia, Canada, Central, France, Germany, etc.

Data Source:

The dataset used in this project is from the AdventureWorks2019 sample database, which is a Microsoft SQL Server database designed to showcase sales and manufacturing operations of a fictitious company that sells bicycles and accessories. For this project, sales-related data from the following tables were used:

    Sales.SalesOrderHeader
    Sales.SalesOrderDetail
    Production.Product
    Production.ProductCategory
    Sales.SalesTerritory

Visuals and Filters:

    Slicers for Interactive Filtering:
        Category: Filter sales data by Accessories, Bikes, Clothing, Components.
        Product: Filter data by individual products such as bike stands, caps, bike wash, and so on.
        Subcategory: Filter by product subcategories.
        Territory: Filter data by different sales regions (e.g., Australia, Canada, Central).

Metrics Calculated:

    Total Sales: The total dollar value of sales per month.
    Running Sales: A cumulative running total of sales for each month.
    Sales Difference: The difference in total sales between consecutive months.

How to Use:

    Filtering: Use the slicers to filter data based on category, product, subcategory, or territory to dynamically update the visualizations.
    Analysis: The charts and tables provide insights into which products and regions contribute the most to sales and how sales trends evolve month by month.
    Monthly Tracking: Compare monthly sales performance and identify key months where there were significant changes in sales.

Tools Used:

    Microsoft Excel: For creating the dashboard, data connections, and visualizations.
    AdventureWorks2019 Database: For providing the data.

Instructions for Replication:

    Import the necessary tables from the AdventureWorks2019 database into Excel.
    Build the pivot tables to calculate sales, order counts, and other metrics.
    Use Excel's built-in chart tools to create visualizations such as pie charts, bar charts, and line charts.
    Add slicers for interactive filtering based on product category, subcategory, and territory.
    Apply formatting and style the dashboard for a clean and professional look.
