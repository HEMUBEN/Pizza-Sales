# PIZZA SALES DASHBOARD
# 1) PIZZA SALES PROJECT
* The Pizza Sales Analysis Project aims to analyze and visualize the sales performance of a pizza restaurant using real transactional data. The dataset contains detailed information such as
  order date,time, pizza category, size, price, and quantity sold. By transforming this raw data into meaningful insights, the project helps identify key trends, customer preferences, and business
  growth opportunities.
* The main objective of this project is to understand the factors that drive revenue and customer demand. Through data cleaning, modeling, and visualization, the analysis uncovers which pizzas are
  most popular, which sizes generate higher profits, and how sales fluctuate over time. This allows business owners to make data-driven decisions such as adjusting menu prices, promoting
  best-selling items, and optimizing operational efficiency.
# 2) 🧠 Technologies & Tools Used
1. Data Storage & Source
Microsoft Excel – Used as the primary data source containing pizza sales transactions, order details, and
pricing information.
CSV/XLSX File Format – Structured format for importing data into analytical tools.
2. Data Cleaning & Preparation
Power Query (in Power BI / Excel) – Used to clean, transform, and format the raw data (handling missing values, changing data types, and creating calculated columns).
Python (optional) – For advanced preprocessing, exploratory data analysis, and automation using libraries like:
pandas – for data manipulation
numpy – for numerical operations
matplotlib / seaborn – for initial visual analysis
3. Data Analysis & Visualization
Power BI – Used to build an interactive dashboard with KPIs, charts, and filters to visualize total revenue, popular pizzas, category-wise sales, and trends over time.
DAX (Data Analysis Expressions) – Used for calculated measures like:
Total Revenue = SUM(pizza_sales[total_price])
Average Order Value = [Total Revenue] / DISTINCTCOUNT(pizza_sales[order_id])
Total Pizzas Sold = SUM(pizza_sales[quantity])
Microsoft Excel (Pivot Tables & Charts) – For creating quick summary reports and trend visualizations.
4. Visualization Tools Used
Visualization Type	Purpose
Bar Chart==> To show top 10 pizzas by revenue and quantity sold
Pie / Donut Chart==> To show sales contribution by category
Line Chart==> To visualize sales trends over time
KPI Cards==> To display key performance indicators like revenue, orders, and AOV
Stacked Column Chart==> To compare pizza sizes and categories
Heat Map==> To show sales by time of day and day of week
5. Reporting & Presentation
Power BI Dashboard – For interactive storytelling and sharing business insights with stakeholders.
Microsoft PowerPoint / Word – For documenting project findings and visual summaries.
# 3) Data Sources Pizza Sales might Connected to
The Pizza Sales dataset (pizza_sales_excel_file.xlsx) was connected to Power BI Desktop through the Excel data connector, cleaned using Power Query, and modeled using DAX for interactive dashboard creation.
# 4) 🍕Features
1. Interactive Dashboard
A fully interactive Power BI dashboard designed to explore pizza sales data visually.
Includes dynamic filters (slicers) for date, pizza category, and size to analyze sales performance from different angles.
Real-time KPIs and charts update automatically based on user selections.
2. Sales Performance Tracking
Displays Total Revenue, Total Orders, Total Pizzas Sold, and Average Order Value (AOV) as key performance indicators (KPIs).
Helps managers monitor overall business performance and identify sales growth or decline periods.
3. Best-Selling Pizzas Analysis
Identifies top-performing pizzas based on both sales revenue and quantity sold.
Highlights which pizza flavors or categories (e.g., Classic, Supreme, Veggie) contribute most to profits.
Provides a clear ranking of pizzas to support marketing and menu decisions.
4. Category and Size Breakdown
Analyzes revenue and quantity sold across pizza categories and sizes (S, M, L, XL).
Reveals which size generates higher sales and which categories are more preferred by customers.
Enables pricing and inventory optimization.
5. Time-Based Sales Insights
Visualizes sales trends by date, month, and time of day to identify peak business hours.
Helps in understanding customer buying patterns — such as lunch/dinner rush hours and weekend performance.
Useful for scheduling staff and managing demand effectively.
6. Revenue Trend Analysis
Line and area charts show daily, weekly, and monthly revenue trends over time.
Enables comparison between different months or categories to evaluate performance improvements.
7. Ingredient-Level Information
The dataset includes pizza ingredients, which allows deep analysis of popular toppings or combinations.
Can help in developing new pizza variants or limited-time offers based on customer preference.
8. Automated Calculations & DAX Measures
Uses DAX formulas in Power BI for automatic calculations of total sales, order counts, and averages.
Reduces manual effort and ensures accuracy in real-time reporting.
# 5) Business Impact & Insights
1. Business Impact
The Pizza Sales Analysis Project provided a data-driven approach to improve decision-making and operational efficiency for the pizza store. By transforming raw sales data into meaningful insights, management can make smarter choices about menu optimization, pricing, and marketing.
Key business impacts include:

*📈 Revenue Growth:
Identifying the top-performing pizzas and sizes helps focus marketing and promotions on high-profit products, directly increasing sales.
*🧠 Customer Understanding:
Analysis of pizza categories, ingredients, and time-based trends reveals customer preferences, enabling targeted offers and improved satisfaction.
*⏰ Operational Efficiency:
Time-based analysis (peak hours and days) allows better workforce scheduling, inventory planning, and delivery management.
*💰 Cost Optimization:
Knowing which pizzas sell less helps reduce waste from slow-moving inventory and ingredients.
*📊 Data-Driven Strategy:
The Power BI dashboard gives leadership real-time visibility into performance metrics, helping make quick, evidence-based business decisions.

2. Key Insights Derived from Analysis
After analyzing the sales data, the following actionable insights were discovered:

# 🥇 Top Performing Pizzas
Italian Supreme, Five Cheese, and Classic Deluxe pizzas generated the highest total revenue.
These items can be promoted further or used as flagship products in marketing campaigns.

# 🍕 Category-Wise Insights
The Classic and Supreme categories contributed the largest share of total revenue.
Veggie pizzas performed steadily, indicating demand among health-conscious customers.

# 📏 Size-Wise Performance
Large (L) and Medium (M) pizzas sold the most, showing customers prefer value-for-money sizes.
Extra Large (XL) pizzas had fewer orders but higher revenue per unit, suggesting potential for premium pricing strategies.

# 📅 Time & Date Trends
Peak order times were during lunch hours (12 PM–2 PM) and evening (6 PM–9 PM).
Friday to Sunday showed the highest order volumes, reflecting weekend demand surges.
This pattern helps optimize staffing and promotional campaigns during high-demand periods.

# 💵 Revenue Insights
Average Order Value (AOV) increased when customers purchased combo or larger-sized pizzas.
Seasonal or festive promotions could further boost high-value orders.

3. Recommendations
Based on insights, the following business strategies are recommended:
*✅ Focus marketing on top 5 pizzas to maximize sales.
*✅ Offer discounts or combos on slow-selling pizzas to balance inventory.
*✅ Increase production during peak hours and weekends to meet customer demand.
*✅ Introduce limited-time offers on popular pizza categories to maintain excitement and engagement.
*✅ Continue tracking KPIs like total revenue, average order value, and category performance in Power BI dashboards.

4. Conclusion
The Pizza Sales Analysis project turned unstructured sales data into actionable insights that helped management understand their business performance clearly. By leveraging Power BI’s analytics and visualization capabilities, the store can make more informed, strategic decisions — ultimately driving higher revenue, reduced waste, and better customer satisfaction.




















