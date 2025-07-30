# Retail_Data_Set
## This project is a comprehensive retail sales data analysis using Python. It extracts actionable insights about product performance, customer behavior, and revenue trends. The dataset includes customer orders with sales, quantity, and product details.The goal is to help businesses understand their performance and support data-driven decisions using exploratory data analysis (EDA) and visualizations.


-<a href = "https://github.com/998rajat/Retail_Data/blob/main/Retail_Sales_Data.csv"> Retail_Data_set</a>

##  Dataset Features

The dataset (`Retail_Dataset.csv`) contains the following columns:

- `OrderDate`: Date when the order was placed
- `Product`: Name of the product
- `Customer`: Name/ID of the customer
- `Quantity`: Number of units sold
- `Price`: Price per unit
- `Sales`: Total revenue (Quantity × Price)

---
##  Project Objectives

- Analyze sales performance over time
- Identify top-performing products and customers
- Visualize trends and patterns using effective charts
- Provide meaningful insights to optimize business strategy

---

##  KPIs & Calculations

| Metric                             | Value / Description                        |
|--------------------------- |--------------------------------------------|
| **Total Sales**            |  Total revenue generated from all orders   |
|  **Average Order Value**   | Mean value per customer transaction        |
|  **Top Products**          | Top 5 products based on quantity sold      |
|  **Monthly Revenue**       | Revenue trend over each calendar month     |
|  **Top Customers**         | Customers with highest total sales         |
|  **Peak Sales Day**        | Day with the highest total revenue         |
|  **Product Order Count**   | Frequency of product orders                |

---

## 📌 Exploratory Analysis & Visualizations

### Monthly Revenue Trend

- Extracted month from `OrderDate` and calculated total sales
- Line chart used to show month-over-month sales trend

### Top 5 Products by Quantity Sold

- Grouped by product and summed quantity
- Identified most in-demand products for marketing or inventory decisions

###  Sales by Product – Bar Chart

- Visual comparison of total sales per product
- Helps identify top revenue-generating items

###  Share of Each Product – Pie Chart

- Product quantity distribution visualized as percentages
- Useful for inventory mix and category-level planning

###  Day with Highest Sales

- Aggregated daily sales
- Revealed top-performing sales day

###  Customer-wise Total Purchase

- Sales grouped by customer
- Identified high-value customers for loyalty targeting

###  Correlation Heatmap (Optional)

- Analyzed relationships between `Quantity`, `Price`, and `Sales`
- Highlights which factors most influence revenue

---

##  Visual Tools Used

- `Pandas`: Data manipulation and groupby operations
- `Matplotlib`: Line plots, bar charts, and pie charts
- `Seaborn`: Advanced charts like heatmaps and catplots
- `Datetime`: For parsing and grouping date-wise records

---

##  Key Business Insights

-  **Majority of sales come from a few key products** — helps with targeted marketing
-  **Customer concentration is visible** — small % of customers contribute to a large % of revenue
-  **Sales fluctuate monthly** — enabling seasonal strategy planning
-  **Bar & pie charts** make inventory and pricing decisions easier
-  **Daily trend analysis** helps schedule future promotions

---

##  Conclusion

This project demonstrates practical data analysis using real-world retail data. It helps stakeholders:

- Understand customer and product behavior
- Make inventory and pricing decisions
- Track performance over time
- Identify top revenue drivers

It also showcases Python skills in data cleaning, EDA, KPI tracking, and visualization — core competencies for any aspiring data analyst or business intelligence professional.






