
Superstore Analytics Report — Tableau Portfolio Project

Short Description / Purpose
Tableau dashboard exploring Superstore sales, profit, and order trends by region, segment, and category. Built with parameters for switching metrics, quick table calculations for regional profit share, a profit-by-state map, and top-product breakdowns. A hands-on project to practice real Tableau workflow.

Tech Stack
- Tableau Desktop / Tableau Public
- Quick Table Calculations (% of Total by Region and Category)
- Parameters (metric switcher: Sales / Profit / Order)
- Dashboard actions and filters (Region, Segment, Year)

Data Source
Sample Superstore — publicly available retail order-level dataset (Category, Sub-Category, Sales, Profit, 
Order, State, Segment, Region), 2014–2017. This is a widely used public/training dataset, 
not proprietary or client data.

Features / Highlights

a) Business Problem
This project simulates a common retail analytics scenario: order-level data spread across states, categories,
and segments, with no single view to answer basic questions — which sub-categories sell the most, which states 
are most/least profitable, and how sales trend over time. As this is a portfolio project on public
sample data, the "business problem" is a practice scenario rather than a real client's.

b) Goal of the Dashboard
- Give a single view of sales, profit margin, and return rate at a glance
- Let a user switch the underlying metric (Sales / Profit / Order) via a parameter, without duplicating charts
- Show geographic performance (profit margin by state) on a map
- Highlight top-performing products and sub-categories
- Break down sale % and profit % contribution by region and category using quick table calculations

c) Walkthrough of Key Visuals
- Analytics Report (main dashboard) — combines KPI cards (Sales, Profit Margin, Return Rate), sub-category bar chart,
  state map, segment donut, top 5 products table, and a sales trend line into one view, with Region 
  and Year filters
- Map by State — profit margin by state using a diverging color scale, with a parameter to switch the underlying metric
- Quick Table Calculations — Sale % and Profit % of total, broken down by Region and Category/Sub-Category,
  showing contribution rather than raw values
- Donut by Segment — order distribution across Consumer, Corporate, and Home Office segments, filterable by region
- Order Trend Line — monthly order trend from 2014–2017 with a trend line overlay
- Sub-Category Bar Charts — sub-categories ranked by order count and by sales, with a reference average line
- Top 5 Products by Sales — parameter-driven table (switches between Sales/Profit/Order) for top 5 products

d) Business Impact & Insight
Observations drawn directly from the sample data used in this project — not outcomes from a real business 
engagement, since this is a practice dataset, not live company data.
- Total sales in this dataset are ~2.30M with a 12.47% profit margin and 5.91% return rate
- Phones and Chairs are the top two sub-categories by sales (330K and 328K), while Fasteners is the lowest at ~3K
- Chairs shows a striking regional split: -230% profit contribution in Central vs +307% in East — meaning
  Central-region chair sales are actively dragging profit down while East is disproportionately profitable
- Tables lose money in Central (-362%) and South (-68%) despite positive sales contribution in those regions
- Consumer is the largest order segment at 51.63%, followed by Corporate (30.23%) and Home Office (18.15%)
- The Canon imageCLASS 2200 Advanced Copier is the single highest-selling product at 61,600 in sales,
   more than double the next product

Screenshots / Demos
![Main Dashboard]([screenshots/finance.jpg](https://github.com/ayush60/Superstore-Analytics-Report-Tableau/blob/main/Superstore-Analytics-Dashboard-Demo.gif))
![Map by State](screenshots/map.jpg)
![Quick Table Calculations](screenshots/Quick_Table_Calculation.jpg)
![Donut by Segment]([screenshots/donut.gif](https://github.com/ayush60/Superstore-Analytics-Report-Tableau/blob/main/sales-by-segment-donut.gif))
![Order Trend Line]([screenshots/Line_Chart.gif](https://github.com/ayush60/Superstore-Analytics-Report-Tableau/blob/main/Order-Trend-by-Month.gif))
![Metric Switch (Parameter)]([screenshots/Metric.gif](https://github.com/ayush60/Superstore-Analytics-Report-Tableau/blob/main/Subcategory-Order-Breakdown%20(Metric).gif))
![Parameter Demo]([screenshots/Parameter.gif](https://github.com/ayush60/Superstore-Analytics-Report-Tableau/blob/main/Subcategory-Sales-Parameter-View.gif))
![Top 5 Products]([screenshots/top_5_product.gif](https://github.com/ayush60/Superstore-Analytics-Report-Tableau/blob/main/Top-5-Products-By-Metric.gif))
