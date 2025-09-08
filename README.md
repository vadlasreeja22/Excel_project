# Excel_project

RETAIL SALES ANALYSIS DASHBOARD USING EXCEL

This project involved the development of a dynamic sales analysis dashboard utilizing Microsoft Excel. The objective was to provide stakeholders with a clear, interactive platform for monitoring key business performance indicators, including total orders, total revenue, average delivery time, and average customer spend.

## 📌  Project Overview

### Data Acquisition & Preparation:

Data Source: The project uses a dataset containing sales records, including details such as order date, occasion, category, and revenue.
Data Cleaning: Ensure the data is clean and correctly formatted. This involves checking for errors, handling missing values, and confirming data types are appropriate for calculations (e.g., numbers for revenue and dates for time-based analysis).

### Dashboard Setup in Excel:

Created a new worksheet to serve as the dashboard's main interface.
Organized the layout with clear sections for KPIs and visualizations.

### Key Performance Indicators (KPIs):

Total Orders: Calculated using a function like COUNT or COUNTA on the order ID column.
Total Revenue: Calculated using the SUM function on the revenue column.
Order Delivery Time: Calculated as the average of the delivery time data.
Avg. Customer's Spent: Calculated by dividing the total revenue by the total number of orders.

 ### Creating PivotTables & Pivot Charts:

PivotTable Creation: Created multiple PivotTables from the raw data to summarize key information.

Revenue by Occasion

Revenue by Category

Revenue by Hour

Revenue by Month

Top 5 Products by Revenue

Top 10 Cities by Orders

Pivot Chart Creation: Converted each PivotTable into a corresponding Pivot Chart for visualization.

Revenue by Occasion: Bar chart.

Revenue by Category: Bar chart.

Revenue by Hour: Line chart.

Revenue by Month: Line chart.

Top 5 Products: Bar chart.

Top 10 Cities: Bar chart.

### Adding Slicers for Interactivity:

Inserted slicers for Order Date, Delivery Date, and Occasion.
Connected each slicer to all relevant PivotTables and Pivot Charts so that we can dynamically filter the entire dashboard with a single click. For example, selecting "Holi" on the Occasion slicer will update all charts to show data for that occasion only.


## 📊 Business Insights:

Sales by Occasion: The dashboard highlighted which occasions (e.g., Holi, Raksha Bandhan, Anniversary) generate the most revenue, allowing the business to plan marketing campaigns and inventory accordingly.

Revenue by Category: The breakdown of revenue by category (e.g., Cake, Colors, Soft Toys) helps identify best-selling product types.

Hourly and Monthly Trends: The line charts for Revenue by Hour and Revenue by Months reveal peak sales times and seasonal trends, which can optimize staffing and promotional timing.

Top Products & Cities: The bar charts for top products and cities identify the most profitable products and geographic areas, guiding decisions on product development, expansion, and distribution.
