# Comprehensive Sales Performance Analysis (Tableau)
This repository contains a comprehensive sales performance analysis project carried out using Tableau. The goal of this project is to provide actionable insights into sales trends, profitability, customer behavior, and geographical performance to inform strategic business decisions.
---


### Table of Contents
- Project Overview

Objectives

Data Source

Methodology

Key Dashboards

Key Insights and Recommendations

How to Use

Repository Structure

Contact

### 📝 Overview
In today's competitive business landscape, understanding sales performance is crucial for sustainable growth. This project leverages Tableau to visualize and analyze sales data, transforming raw information into clear, interactive dashboards. The analysis covers various aspects of sales, including overall key metrics, customer profitability, product performance, sales by category, and geographical distribution.
---

### 🎯 Objectives
The primary objectives of this sales performance analysis are to:
1. Monitor Key Sales Metrics: Track essential performance indicators such as Profit, Profit Ratio, Sales, Order Count, Average Order Value (AOV), and Average Days to Ship.
2. Identify Profitable and Unprofitable Customers: Segment customers based on their profitability to inform targeted marketing and sales strategies.
3. Analyze Sales by Category and Sub-Category: Understand which product categories and sub-categories are driving the most revenue and profit.
4. Assess Geographical Performance: Identify top-performing states/regions and areas with potential for growth or requiring intervention.
5. Evaluate Product Performance: Determine the best-selling and most profitable products.
6. Analyze Revenue by Ship Mode: Understand the impact of different shipping methods on revenue across sub-categories.
7. Examine Order Origin: Gain insights into the percentage of orders by country of manufacture.
8. Provide Actionable Insights: Generate data-driven recommendations to optimize sales strategies, improve profitability, and enhance operational efficiency.
---

### Data Source
The analysis is based on a sales dataset, typically containing information such as:
- Order Details: Order Date, Ship Date, Order ID
- Product Information: Product ID, Product Name, Category, Sub-Category
- Sales Metrics: Sales, Profit, Quantity
- Customer Information: Customer ID, Customer Name, Segment
- Geographical Data: State, Region, Country
- Shipping Information: Ship Mode
---

### Methodology
1. Data Connection & Preparation:
- Connected to the raw sales data in Tableau.
- I used unique identifier of each dimension table to establish an inner join with sales fact table.
- Performed necessary data cleaning and transformations (e.g., date formatting, creating calculated fields for profit ratio, AOV, etc.).

2. Dashboard Design & Development:
- Created multiple interactive dashboards, each focusing on a specific aspect of sales performance.
- Utilized various chart types (bar charts, line charts, scatter plots, treemaps, maps, pie charts, tables) to effectively visualize the data.
- Implemented filters (e.g., OrderDate, Segment, Top N Sales) to allow for dynamic exploration of the data.
- Ensured a clean, intuitive, and visually appealing layout for easy interpretation.

3. Analysis and Interpretation:
- Analyzed trends and patterns within each dashboard.
- Identified key insights related to profitability, top performers, areas for improvement, and potential risks.
- Formulated actionable recommendations based on the data.
---

Key Dashboards
The project includes the following key dashboards:

1. Sales Overview Dashboard
This dashboard provides a high-level summary of key sales metrics and overall performance

- Components:

 - Key Metrics: Displays Profit, Profit Ratio, Sales, Order Count, AOV, and Avg. Days to Ship.
 - Profitable vs Unprofitable Customers: A scatter plot showing customer sales vs. profit, highlighting profitable and unprofitable segments.
 - Sales By Category/Subcategory: Bar chart illustrating sales distribution across different product categories.
 - Profit by Month: A line chart showing monthly profit trends, with an option to highlight specific categories.
 - % of Orders by Country of Manufacture: A pie chart showing the distribution of orders by country of origin (e.g., United States, Canada).

2. Performance by Location Dashboard
This dashboard focuses on geographical sales performance.

- Components:
  - Top N States by Sales: A bar chart displaying the top N states based on sales, with a dynamic filter to adjust N.
  - States by Sales (Map): A choropleth map visualizing sales performance across different states, color-coded by region.
  - Sales by State (Table): A detailed table showing sales figures for each state across different years.
  - Top 10 Product by Sales: A treemap showing the top products by sales, with color representing profitability.
 
3. Revenue by Ship Mode & Sub-Category Dashboard
This dashboard provides a detailed breakdown of revenue by shipping mode and product sub-category.

- Components:
  - Revenue By Ship Mode & Sub-Category Table: A detailed table showing revenue for each sub-category across different shipping modes (First Class, Same Day, Second Class, Standard Class). This helps identify which sub-categories perform best with certain shipping methods.
 ---

### 💡Key Insights and Recommendations
1. Customer Profitability Optimization: Conduct a deeper analysis into the characteristics of these unprofitable customers. This could involve examining their purchase history, return rates, discount utilization, or service costs. Develop targeted strategies to either improve their profitability (e.g., through upselling, cross-selling, or reducing service costs) or re-evaluate the viability of serving these segments.
  
2. Geographic Sales Focus: California, New York, and Texas consistently rank as the top states by sales.

- Recommendation: Continue to invest in these high-performing regions to maximize market penetration. Simultaneously, identify states with moderate sales and explore opportunities for growth through targeted marketing campaigns or sales initiatives. The regional breakdown on the map can guide resource allocation.

3. Product Portfolio Management: Technology is the leading sales category, and certain products (e.g., TEC-CO-10004722-1-1, TEC-MA-10001047-2-1) are significant revenue drivers.

- Recommendation: Leverage the success of top-performing products and categories by investing in their continued development and promotion. For products with high sales but low profitability (if any are identified), investigate cost structures or pricing strategies. Conversely, for highly profitable but lower-volume products, explore ways to increase their market visibility and sales.

4. Shipping Mode Efficiency: The "Revenue by Ship Mode & Sub-Category" dashboard reveals how different shipping methods contribute to revenue across various product sub-categories.

- Recommendation: Analyze the preferred shipping modes for high-value or high-volume sub-categories. Optimize logistics and shipping partnerships based on these insights to reduce costs or improve delivery times, thereby enhancing customer satisfaction and potentially increasing sales.

Overall Sales Health & Trends: The key metrics show healthy overall sales and profit ratios, with monthly profit trends indicating seasonality or growth patterns.
---

### How to Use
To view and interact with these dashboards:
- Tableau Desktop: If you have Tableau Desktop, you can open the .twbx file directly.
- Tableau Reader: If you don't have Tableau Desktop, you can download Tableau Reader (free) to open and interact with the packaged workbook.
- Tableau Public: The dashboards might be published to Tableau Public. A link will be provided here if available.

Placeholder: [VIEW](https://public.tableau.com/app/profile/chukwudumeje.oforah/viz/ComprehensiveSalesPerformanceAnalysis/SalesDashboard)

---
### 📜 License
This project uses the Sample Sales Dataset provided by [Corporate Finance Institute Canada](https://corporatefinanceinstitute.com/), intended for educational and analytical demonstration purposes.

---
### 🙋‍♂️ About the Analyst
I’m a Data Analyst passionate about uncovering patterns in consumer markets. I specialize in Excel, Power BI, SQL, and Python for data storytelling and automation. Through this project, I demonstrated the power of local market analytics in decision-making.
📬 Contact
- [LinkedIn](https://www.linkedin.com/in/oforah/)
- [Email](chukwudumejeoforah@gmail.com)
- [Portfolio](https://oforah007.github.io/Website-Demo/)





