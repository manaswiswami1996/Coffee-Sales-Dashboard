![logo](https://github.com/manaswiswami1996/Coffee-Sales-Dashboard/blob/83d269f8140b6c93c83f5d44ee1f67522e0ca08b/Coffee%20Sales%20Banner.jpg)
# Morocco Coffee-Sales-Dashboard
In this project, an analysis of coffee sales is done through various parameters using MS-Excel. After data cleaning and processing, an interactive dashboard is created to help the client understand how the sales have performed across time, products and other parameters.The project demonstrates advanced Excel skills, including data preprocessing, and the use of PivotTables, PivotCharts, slicers, and timeline filters to create a fully interactive experience.

## Dashboard Preview
![Coffee Sales Dashboard](https://github.com/user-attachments/assets/92ef8bdb-0198-4fad-9e9b-7d18332c7fd2)

## Features
The Coffee Sales Dashboard includes the following key components:
- *Total Sales Over Time:* A line chart showing total sales trends from 2019 to 2022, broken down by different coffee types (Arabica, Excelsa, Liberica, and Robusta).
- *Sales by Country:* A bar chart displaying total sales across key regions, including the United States, Ireland, and the United Kingdom.
- *Top Customers:* A leaderboard of the top 5 customers based on total sales.
- *Average Order Value by Size:* A line chart showing the average order value segmented by coffee package size (0.2 kg, 0.5 kg, 1.0 kg, 2.5 kg).

  #### Filters:
 - Order Date: A timeline filter to focus on specific periods (monthly/quarterly/yearly views).
 - Country: Filter sales data by region.
 - Roast Type: Drill down to view sales by roast type (Dark, Medium, Light).
 - Loyalty Score: Analyze data based on whether customers have a loyalty card or not.

## Data Preprocessing
Before creating the dashboard, several data preprocessing steps were performed using advanced Excel functions:
- XLOOKUP: Used to dynamically retrieve values from related tables, such as matching customer details based on Customer ID and product details based on Product ID. This helped in creating a comprehensive dataset linking orders, customers, and products. 
- INDEX MATCH: Employed for more complex lookups, especially when dealing with multiple criteria. This was used to match products and retrieve corresponding information like unit price and size.
Key Metrics
- Total Sales: Aggregated sales across the dataset.
- Top Coffee Products: Popular coffee types based on sales and profitability.
- Sales by Country: Sales distribution across regions.
- Average Order Value (AOV): The average spend per order, segmented by coffee package size.
- Customer Loyalty: Breakdown of sales by customers with and without loyalty cards.

##  Tools and Techniques
This project demonstrates the following Excel features:
- XLOOKUP & INDEX MATCH: Advanced lookup functions to merge datasets and retrieve necessary information dynamically.
- PivotTables & PivotCharts: Used to summarize and visualize data in an interactive manner.
- Slicers and Timelines: Filters that allow users to quickly interact with the dashboard and view segmented data.
- Advanced Formulas: Calculated fields for metrics like total sales and average order value.
- Data Cleaning and Transformation: Pre-processing of data using Excel's data handling tools.

## Insights
- Liberica and Excelsa contribute the highest sales but could be under-marketed. Target promotions for these coffee types with loyalty program incentives to retain high-value customers.
- Sales see significant spikes in June, October, and December across years. Focus marketing campaigns, discounts, and bundle offers during these months to capitalize on consumer interest.
- Products like L-L-2.5 (Liberica, Light Roast) and L-M-2.5 (Liberica, Medium Roast) generate the highest profit margins. Bundle these with popular but lower-profit items to maximize revenue per order.
- Robusta contributes the least sales among coffee types. A strategy to highlight its unique qualities (e.g., stronger flavor, affordability) via targeted ads or sampling campaigns could help improve its market share.
- While the data predominantly shows high sales in the United States and Ireland, explore marketing in regions with emerging coffee trends.

## Data Source
The dataset used for this project contains:
- Orders: Information about individual coffee orders (Order ID, Order Date, Product, Quantity, Sales).
- Customers: Customer details, including location and loyalty card information.
- Products: Coffee products offered, including product type, roast, size, and pricing

