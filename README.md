Coffee Shop Sales Analytics Dashboard ☕📊
This repository features an Excel-based dashboard designed for comprehensive analysis of coffee shop sales transactions. This dashboard provides valuable insights into product performance, store efficiency, sales trends, and peak hours, empowering better business decisions and operational optimization.

Features ✨
This dashboard enables detailed analysis through various key metrics and visualizations, covering:

Sales Performance Overview:
Total revenue generated (Total Bill).
Breakdown of sales by Product Category (e.g., Coffee, Tea, Bakery, Food, Coffee beans, Merchandise, Pastries), Product Type (e.g., Brewed herbal tea, Gourmet brewed coffee, Barista Espresso, etc.), and Product Detail.
Analysis of sales by Size (e.g., Large, Regular, Small) to understand customer preferences.
Total transaction_qty (quantity sold).

Store and Location Analysis:
Performance insights across different store_location (e.g., Astoria, Lower Manhattan, Hell's Kitchen).
Comparison of sales metrics per store_id.

Temporal Sales Trends:
Daily, weekly, and monthly sales patterns using transaction_date, Month Name, Day Name, Day of Week, and Month.
Hourly sales analysis using Hour to identify peak operating times.

Product Deep Dive:
Identify best-selling products by product_category, product_type, and product_detail.
Analyze unit_price and its relation to Total Bill and transaction_qty.

Data Sources 📋
The dashboard is built upon detailed transactional data from coffee shop sales. The primary dataset is expected to contain columns such as:
transaction_id: Unique identifier for each transaction.
transaction_date: Date of the transaction.
transaction_time: Time of the transaction.
store_id: Unique identifier for the store location.
store_location: Name of the store location (e.g., Astoria, Lower Manhattan).
product_id: Unique identifier for the product.
transaction_qty: Quantity of the product sold in the transaction.
unit_price: Price per unit of the product.
product_category: Broad category of the product (e.g., Coffee, Tea).
product_type: Specific type of product within a category (e.g., Brewed herbal tea, Gourmet brewed coffee).
product_detail: Further detail about the product (e.g., Peppermint, Ethiopia, Brazilian).
Size: Size of the product (e.g., Large, Regular, Small, Not defined).
Total Bill: Total amount of the transaction.
Month Name: Month of the transaction (e.g., January, February).
Day Name: Day of the week of the transaction (e.g., Monday, Tuesday).
Hour: Hour of the day the transaction occurred.
Day of Week: Numeric representation of the day of the week.
Month: Numeric representation of the month.
