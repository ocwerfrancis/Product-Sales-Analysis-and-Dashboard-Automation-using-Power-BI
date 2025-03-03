# Product-Sales-Analysis-and-Dashboard-Automation-using-Power-BI
# Project Objective:
Develop an interactive Power BI dashboard that provides real-time insights into product sales, costs, and profits. The goal is to empower the client with dynamic visualizations and data-driven decision-making tools.
# Key Business Questions Addressed:
## Product Performance:

- **Top 5 products by total sales:** Identify the products generating the most revenue.
- **Bottom 5 products by total sales:** Highlight underperforming products.
- **Top 5 products by quantity sold:** Showcase the best-selling items by volume.
- **Bottom 5 products by quantity sold:** Spot the products with the lowest sales volume.
## Financial Trends:

- **Monthly trends:** Visualize sales, costs, and net profit over time.
- **Profitability:** Monitor total sales ($1.47M), costs ($956K), and net profit ($513K).
## Order and Customer Insights:

- **Order status:** Analyze completed (48.39%) vs. returned (51.61%) orders.
- **Top 5 buying customers:** Identify the most valuable clients by sales volume.
- **Total number of orders:** Track the number of processed orders (555).
## Geographic and Payment Analysis:

- **Sales by country:** Explore the regions contributing most to revenue (Nigeria, Australia, UK, etc.).
- **Sales by payment method:** Understand preferred payment options (bank transfer, cash, credit card, mobile).
## Data Analysis Process:
### 1. Data Collection:
Collect data on:

- **Products:** names, categories, prices, costs, quantities sold
- **Orders:** order ID, status (completed/returned)
- **Customers:** names, locations, and total spend
- **Payments:** methods (cash, mobile, card, etc.)
- **Geography:** countries
### 2. Data Cleaning:
Performed in Power Query to:

- Remove duplicates
- Handle null values
- Standardize product and country names
- Format numeric columns (sales, costs, profits)
### 3. Data Modeling:
- Create relationships between Products, Orders, Customers, and Payments tables
- Define calculated columns and measures (e.g., Total Sales, Net Profit)
- Implement DAX formulas for ranking and aggregation
### 4. Data Visualization:
- **KPI Cards:** Display total sales, cost, profit, average sales, and order count
- **Bar Charts:** Show top/bottom products by sales and quantity
- **Line Graphs:** Track sales trends by month
- **Pie Charts:** Illustrate order status and payment method breakdown
- **Maps:** Visualize sales distribution by country
- **Tables:** Rank top 5 buying customers and product sales details
## Deliverables:
### Interactive Power BI Dashboard:

- Filters for Order Status and Country
- Year toggles (2024, 2025) to view historical data
- Dynamic charts that auto-update with refreshed data
