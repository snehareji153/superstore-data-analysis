
# Superstore Sales Analysis - Power BI Project

A brief description of what this project does 


 Problem Statement

The objective of this project is to analyze Superstore's sales data to identify key trends and insights related to customer behavior, shipping performance, product profitability, and regional performance. 

The goal is to use Power BI to:

1. Understand sales performance by segment, category, and region.

2. Evaluate shipping delays and their impact.


Steps Involved


1.  Data Loading & Cleaning

1.Imported Superstore data (.csv/.xlsx) into Power BI.

2.Performed data type conversions .

3.Created calculated columns:

Profit Margin = Profit / Sales

Shipping Status (Delayed vs On-Time)

4.Created calculated measures
total sales----total_sales = SUM('Sample - Superstore'[Sales])
total profit-----Total profit = SUM('Sample - Superstore'[Profit])
total orders-----total_orders = COUNT('Sample - Superstore'[Order ID])


2.  Visualizations Created
 Sales & Profit Overview
KPIs: Total Sales, Total Profit, Profit Margin,Total orders

slicers- Product name, subcategory name, city,region, State

Bar chart: Sales & Profit by Segment/Category,Avarage of shipping duration by shipping mode, Average of sales by shipping duration region,Average of sales by subcategory and region

Column chart-shipping duration by state

Area chart-- sum of sales by year and months,sum of sales by year and quarter


 Regional Performance
Map visualization: total customers  by Region/State

Shipping Performance
Bar chart: Shipping Status (Delayed vs On Time)

Donut chart: Proportion of orders by shipping status

 Dashboard Insights – Superstore Sales Performance

 KPI Cards 
 Total Sales:

$159K worth of sales made.

Indicates a decent volume, but further trend analysis (YoY, MoM) is needed.

Total Profit:

$21K profit generated from total sales.

Profitability is positive but not high relative to sales (13.2% profit margin).

 Overall Profit Margin:

Displayed as $137.79K, likely a calculation or formatting issue.

It should ideally be shown as a percentage (Profit / Sales).

Total Orders:

769 orders placed.

Useful for calculating AOV (Average Order Value): $159K / 769 ≈ $207/order.

 Profit by Category 
Technology is the most profitable category (~$11.6K).

Office Supplies brings moderate profit (~$7.7K).

Furniture generates the lowest profit (~$2.1K).

 Insight: Technology drives most of the store’s profitability.

 Sales by Category
Technology leads in sales (~$61K).

Furniture and Office Supplies follow closely (~$50K and ~$48K).

 Insight: Despite similar sales levels, Furniture underperforms in profit → likely due to high costs or discounts.



Regional Performance

 Sum of Sales by Region
West: Highest sales at $0.73M

East: Close second at $0.68M

Central: $0.50M

South: Lowest at $0.39M

 Sum of Profit by Region
West leads in profit: $108K

East follows: $92K

South and Central trail with significantly lower profits ($47K and $40K respectively)

 Insight: The West and East regions are the most lucrative in terms of both sales and profit. South and Central regions may need strategic pricing, promotion, or operational improvements.

 Shipping Insights
 Average Shipping Duration by Ship Mode
Standard Class: Longest avg. delivery time (5.01 days)

Second Class: 3.24 days

First Class: 2.18 days

Same Day: Fastest (0.04 days)

 Shipping Status (Order Count)
Delayed Orders: 67.71%

On-Time Orders: Only 32.29%

 Insight: Majority of orders are delayed, especially for Standard and Second Class. This can impact customer satisfaction and retention. There’s an opportunity to optimize logistics or promote faster shipping options.

 Product-Level Analysis
Top 10 Products by Profit
Canon imageCLASS 2200 is the top profit driver (51.85% of total product profit).

Other high contributors:

Fellowes PB500: 15.95%

HP DesignJet 1055cm: 8.43%

Canon PC160: 9.4%

 Insight: Canon printers and tech accessories dominate profitability. These items could be promoted further through bundles or cross-sells.

 Sum of Sales by Product Name
Again, Canon imageCLASS 2200 dominates (40.16% of product-level sales).

Other notable contributors:

Fellowes PB: 17.9%

Cisco TelePresence System: 14.76%

 Insight: Profit and sales are heavily concentrated in a few high-performing tech products, indicating a need to diversify or strengthen marketing around other products.

 City-Wise Profit
Seattle: Highest profit ($29,156)

Los Angeles: $30,447 (possibly the top performer depending on final values)

Other cities performing well: San Francisco, Detroit, Lafayette

 Insight: Focus sales and support efforts in top-performing cities. Consider regional promotions or dedicated campaigns in underperforming locations.

 Overall Recommendations
 Optimize Shipping: High delays must be addressed—consider revisiting courier partners or incentivizing fast shipping.

 Double Down on Top Products: Continue promoting top-sellers like Canon printers and Fellowes devices.

 Regional Strategy:

Prioritize the West & East regions for growth.

Investigate performance issues in the South & Central.

 Customer Experience: With ~68% delayed orders, investigate bottlenecks in fulfillment or supply chain.

  Sales Trend Over Time
 Sum of Sales by Year and Month
Seasonality observed: Sales spike around July, November, and December each year.

Notable peaks:

July 2014: ~82K

November 2014: ~70K

November 2015: ~65K

December 2016: ~76K

February and March generally show lower sales across all years.

 Insight: Strong seasonality effect—likely linked to holiday shopping cycles and fiscal year-end incentives. These months should be key targets for marketing and promotional campaigns.

 Sum of Sales by Year and Quarter
Clear year-over-year growth:

Q4 2014: ~0.14M → Q4 2017: ~0.28M (doubled in 3 years)

Strongest quarters consistently:

Q2 & Q4 in every year (April–June, Oct–Dec)

 Insight: Q2 and Q4 are high-performing quarters. This could guide inventory planning, staffing, and advertising budgets for those periods.

 Customer & Geographic Insights
 Count of Customer Name by Location (Map)
Dense clusters in:

California (esp. Los Angeles, San Francisco)

New York & East Coast

Texas and Midwest states

Sparse representation in:

Mountain states (Wyoming, Montana)

Most of the Deep South

 Insight: Focus efforts on high-density areas for retargeting and loyalty programs. Opportunity exists to expand into underpenetrated regions.

 Shipping Efficiency
 Average Shipping Duration by City
Majority of cities have shipping durations clustered between 2 and 5 days.

Outliers exist up to 7 days, possibly in remote locations.

 Insight: Standard shipping duration is consistent, but some cities experience longer wait times. Investigate logistics inefficiencies in outlier cities and consider regional distribution center improvements.

 Strategic Recommendations
Double Down on Seasonal Peaks:

Align campaigns with Q2 and Q4

Run flash sales in July and November–December

Enhance Distribution:

Explore warehouse optimization to reduce delivery times in slower cities.

Regional Expansion:

Focus growth initiatives in underrepresented states

Consider localized promotions to improve customer acquisition

Customer Density Leverage:

Launch geo-targeted campaigns in high-density cities like LA, SF, NY, Chicago
