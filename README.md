# SSRS Reports of AdventureWorks

This repository contains a collection of **SQL Server Reporting Services (SSRS)** paginated reports built using the classic **AdventureWorks** sample database (Microsoft's standard OLTP sample for SQL Server). These reports provide key business insights for sales, performance, inventory, HR, and more.

The reports focus on practical analytics scenarios such as top performers, trends, variances, and shortages — ideal for learning SSRS, demonstrating reporting capabilities, or using as templates.

## Reports Included

All reports are sourced from AdventureWorks data and showcase various SSRS features like charts, tables, matrices, parameters, drill-down, conditional formatting, and gauges.

1. **BestSaleProducts**  
   Displays the top-selling products by revenue/quantity, often with bar charts or ranked tables.  
   ![Best Sale Products Report](Report%20Figures/BestSaleProducts.png "Top products by sales in AdventureWorks")

2. **HeadCountByDepartment**  
   Shows employee headcount distribution across departments (bar chart or table from HumanResources schema).  
   ![Head Count by Department](Report%20Figures/HeadCountByDepartment.png "Employee headcount grouped by department")

3. **MarginByCategory**  
   Analyzes profit margins by product category/subcategory (pie, bar, or matrix with conditional colors).  
   ![Margin by Category](Report%20Figures/MarginByCategory.png "Profit margin breakdown by product category")

4. **MonthlySaleTrend**  
   Visualizes monthly sales trends over time (line chart with possible year-over-year comparison).  
   ![Monthly Sales Trend](Report%20Figures/MonthlySaleTrend.png "Sales trend line chart by month")

5. **ProductsShortage**  
   Identifies products with low stock, potential shortages, or inventory alerts (table with thresholds or alerts).  
   ![Products Shortage Report](Report%20Figures/ProductsShortage.png "Inventory shortage and low stock products")

6. **SaleVSQuota**  
   Compares actual sales vs sales quotas/targets for employees or teams (gauges, bars, or performance indicators).  
   ![Sales vs Quota](Report%20Figures/SaleVSQuota.png "Actual sales compared to quota with performance status")

7. **TopCustomersbyYTDSales**  
   Ranks top customers by year-to-date (YTD) sales revenue (bar chart or table with drill-through potential).  
   ![Top Customers by YTD Sales](Report%20Figures/TopCustomersbyYTDSales.png "Top customers ranked by year-to-date sales")


## Features Demonstrated

- Parameterized reports (date ranges, categories, etc.)
- Interactive elements (drill-down, sorting, expand/collapse)
- Visualizations: Charts (bar, line, pie), gauges, sparklines
- Formatting: Conditional coloring, indicators (red/yellow/green)
- Data sources: AdventureWorks OLTP database

## Setup Instructions

1. **Prerequisites**
   - SQL Server with AdventureWorks database installed (download from [Microsoft GitHub samples](https://github.com/microsoft/sql-server-samples/releases/tag/adventureworks)).
   - SQL Server Data Tools (SSDT) or Visual Studio with Reporting Services installed.
   - SSRS Report Server (native mode or Power BI Report Server).

2. **Restore Database**
   - Download and restore `AdventureWorks2022.bak` (or compatible version) to your SQL Server instance.

3. **Open & Deploy Reports**
   - [Clone this repo](Reports.rdl).
   - Open the `.rdl` files in Report Builder or Visual Studio.
   - Update the data source connection string to point to your AdventureWorks database.
   - Deploy to your SSRS server or run locally in preview mode.

## Screenshots Gallery

Here are preview images of the reports (hover for titles):

<grok-card data-id="ecf193" data-type="image_card" data-plain-type="render_searched_image"  data-arg-size="LARGE" ></grok-card>



<grok-card data-id="d40f5a" data-type="image_card" data-plain-type="render_searched_image"  data-arg-size="LARGE" ></grok-card>



<grok-card data-id="27bd47" data-type="image_card" data-plain-type="render_searched_image"  data-arg-size="LARGE" ></grok-card>



<grok-card data-id="6f8f81" data-type="image_card" data-plain-type="render_searched_image"  data-arg-size="LARGE" ></grok-card>


(These are representative AdventureWorks SSRS-style reports; your exact outputs may vary slightly based on parameters and styling.)

## Contributing

Feel free to fork, improve visualizations, add parameters, or create new reports! Pull requests welcome.

## License

MIT License – free to use, modify, and distribute.

Questions or issues? Open an issue in this repo.
