# Reinforcement-Business-Intelligence-Operations-Analytics
## Project Overview
This project is an automated business intelligence and performance monitoring solution developed for a reinforcement steel business.
The solution uses Microsoft Power BI to consolidate and analyze daily and monthly transactions across sales, customers, procurement, suppliers, inventory, expenses, profitability, and financial performance.
The objective was to move beyond simply reporting historical numbers and build a system that helps management understand:
•	What is happening in the business?
•	Why is it happening?
•	Where are the risks?
•	Where are the cost-saving opportunities?
•	Which products and customers are driving performance?
•	What actions should management take?
The Power BI model is structured to allow new transaction data to be refreshed, automatically updating the connected dashboards and business metrics

## Business Problem
Businesses that rely on manually prepared reports can struggle to maintain a consistent view of their daily operations.
Sales, purchases, expenses, inventory and supplier information may exist in different records, making it difficult to quickly identify:
•	Revenue changes
•	Profitability problems
•	Supplier pricing differences
•	Inventory shortages
•	Slow-moving stock
•	Customer concentration
•	Procurement opportunities
•	Working-capital risks
This project addresses this problem by creating a centralized and automated reporting solution for ongoing business monitoring.

## Business Objectives 

The solution was designed to help management:
1.	Monitor daily and monthly business performance.
2.	Track revenue, costs, profit and expenses.
3.	Understand customer and product performance.
4.	Evaluate supplier pricing and procurement efficiency.
5.	Identify potential supplier cost savings.
6.	Monitor inventory availability and working capital.
7.	Identify profitable and underperforming products.
8.	Detect operational risks early.
9.	Support data-driven business decisions.

## Automated Reporting Workflow

Daily Transactions
       ↓
Sales / Purchases / Expenses / Inventory Data
       ↓
Data Cleaning & Transformation
       ↓
Power BI Data Model
       ↓
DAX Measures & Business Logic
       ↓
Automated Dashboard Refresh
       ↓
Daily & Monthly Performance Monitoring
       ↓
Business Insights
       ↓
Management Decisions
<p>
  
</p>
The solution is designed as a repeatable reporting framework, rather than a one-time analysis.
As new transactions are added and the data is refreshed, the connected dashboards and measures update accordingly.

## Tools & Technologies

•	Microsoft Power BI
•	DAX
•	Power Query
•	Microsoft Excel
•	Data Cleaning & Transformation
•	Data Modeling
•	Business Intelligence
•	Procurement Analytics
•	Inventory Analytics
•	Customer Analytics
•	Financial Analysis

## Dataset

## Executive Overview
Provides management with a one-page summary of overall business performance.

<img width="622" height="372" alt="Executive_dashboard" src="https://github.com/Debbyjones99/Reinforcement-Business-Intelligence-Operations-Analytics/blob/main/Dashboard%20Screenshots/Executive%20Dashboard.png
" />
<img width="622" height="372" alt="Executive_dashboard" src="http://github.com/Debbyjones99/Reinforcement-Business-Intelligence-Operations-Analytics/blob/main/Dashboard%20Screenshots/Executive%20Dashboard.png" />

### Key Questions
•	How is the business performing overall?
•	Are we making money?
•	Is profitability improving?
•	Are expenses under control?
•	What risks require immediate attention?

1. Overall Dashboard — May & June
   
Key Findings
Revenue: ₦30.3M
Quantity Sold: 1.4K
Net Profit: ₦4.9M
Gross Profit %: 21.9%
Inventory Value: ₦26.8M
2. May & June Dashboard — Monthly Performance

<img width="622" height="372" alt="May performance Executive_dashboard" src="https://github.com/Debbyjones99/Reinforcement-Business-Intelligence-Operations-Analytics/blob/main/Dashboard%20Screenshots/May%20performance%20(Executive%20dashboard).png
" />
<img width="622" height="372" alt="June performance Executive_dashboard" src="https://github.com/Debbyjones99/Reinforcement-Business-Intelligence-Operations-Analytics/blob/main/Dashboard%20Screenshots/June%20performance%20(Executive%20dashboard).png
" />

### Key Findings
•	Revenue declined by 31.3% from May to June.
•	Quantity sold declined by 28.3%.
•	Net profit declined by 35.1%.
•	Gross margin remained relatively stable, increasing from 21.8% to 21.9%.
•	Expense ratio increased from 5.4% to 6.4%.
•	Inventory risk remained significant, with multiple materials reaching critical or negative stock positions.
### Executive Takeaway
The business remained profitable, but the decline in revenue and profit, combined with an increasing expense ratio and inventory risk, requires management attention.

## Sales & Customer Intelligence

This dashboard focuses on customer behaviour, sales performance, products, manufacturers and purchasing patterns.

<img width="622" height="372" alt="Sales & Customer Intelligence" src="https://github.com/Debbyjones99/Reinforcement-Business-Intelligence-Operations-Analytics/blob/main/Dashboard%20Screenshots/Sales%20%26%20Customers%20intelligence.png
" />
### Key Questions
•	Which customers generate the most revenue?
•	Which products sell the most?
•	Which products generate the most revenue?
•	What are customers buying?
•	How much does the average customer order?
•	Which manufacturers and sizes drive sales?

### Key Findings
Metric	Overall	May	June
Quantity Sold	1.4K	831	596
AOV	₦151.52K	₦158.9K	₦141.87K
Average Selling Price	₦21.24K	₦21.61K	₦20.71K

*Customer Insight*
Customer C009 generated the highest overall revenue at approximately ₦1.63M.
Product Insight
M006 generated the highest overall product revenue at approximately ₦3.13M.
Size Insight
The 25mm reinforcement size generated the highest revenue at approximately ₦9.08M.
Manufacturer Insight
Quantum generated the highest manufacturer revenue at approximately ₦9.15M, representing approximately 30.2% of total revenue.

## Procurement & Supplier Performance

This dashboard evaluates supplier pricing, purchase volumes, supplier cost variance and potential procurement savings

<img width="622" height="372" alt="Procurement & Supplier Performance" src="https://github.com/Debbyjones99/Reinforcement-Business-Intelligence-Operations-Analytics/blob/main/Dashboard%20Screenshots/Procurement%20%26%20Supplier%20Performance.png
" />

### Key Questions
•	Which supplier provides the best value?
•	Which supplier is overpriced?
•	Which supplier supplies the largest quantity?
•	Are suppliers charging above standard cost?
•	How much could potentially be saved by switching suppliers?

### Key Findings
•	Total purchase cost: ₦53.8M
•	Total quantity purchased: 2.9K units
•	Supplier cost variance: approximately ₦3.3M
•	Potential supplier savings: approximately ₦1.15M
•	Mega Steel supplied the highest quantity at 765 units.
•	Mega Steel recorded the highest supplier cost variance at approximately ₦1.07M.

### Supplier Savings Analysis

The potential savings analysis was refined to compare supplier prices for the:

Same manufacturer + same material size
rather than comparing every supplier against one overall lowest price.
This provides a more comparable and conservative estimate of the procurement opportunity.
*Potential Opportunity*
₦1.15M estimated potential supplier savings
The estimate assumes that product quality, specifications, delivery requirements, payment terms and other commercial conditions are comparable.

## Product Profitability & Inventory Intelligence
This dashboard combines product profitability with inventory performance.
<img width="622" height="372" alt="Product Profitability & Inventory Intelligence" src="https://github.com/Debbyjones99/Reinforcement-Business-Intelligence-Operations-Analytics/blob/main/Dashboard%20Screenshots/Inventory%20%26%20Product%20Profitability.png
" />

### Key Questions
•	Which products generate the most profit?
•	Which products have strong margins?
•	Which products are slow-moving?
•	Which products are tying up capital?
•	Which products require pricing or inventory review?

### Key Findings
•	Overall gross profit: approximately ₦6.6M
•	May gross profit: approximately ₦3.9M
•	June gross profit: approximately ₦2.7M
•	Overall stock on hand: approximately 1.5K units
•	M012 generated the highest overall gross profit at approximately ₦671.8K.
•	M005 had the highest inventory value at approximately ₦4.83M.

### Profitability Insight

M006 contributed approximately 9% of revenue but generated about 21% of total profit.
This indicates that M006 contributes disproportionately to profitability and may deserve further attention in inventory planning, marketing and procurement strategy.

## Inventory Intelligence
This dashboard focuses on stock availability, inventory value, inventory turnover, slow-moving products and working-capital risk.
<img width="622" height="372" alt="Inventory Intelligence" src="https://github.com/Debbyjones99/Reinforcement-Business-Intelligence-Operations-Analytics/blob/main/Dashboard%20Screenshots/Stock%20inventory%20analysis.png
" />
### Key Questions
•	Which products are at risk of running out?
•	Which products are sitting too long?
•	Which products require replenishment?
•	Which products are tying up cash?

*Slow-Moving Inventory*
*Product	Inventory Value	Days in Stock*
M005	₦4.83M	245 days
M020	₦1.30M	297 days
M002	₦1.39M	195 days
M007	₦1.17M	372 days

### Key Insight
M005 had the highest inventory value at ₦4.83M.
Of the 296 units purchased, only 59 units were sold, indicating that a significant amount of capital may be tied up in slow-moving inventory.
Stock Risk
Several materials recorded negative stock positions.
For this sample dataset, the negative balances represent situations where recorded sales exceeded recorded purchases, such as stock being sourced temporarily from neighbouring businesses.
In a real business environment, negative stock would require investigation because it could indicate:
•	Missing purchase records
•	Timing differences
•	Unrecorded stock movements
•	Borrowed inventory
•	Inventory control issues

## Key Business Insights
The analysis revealed several important business signals:
1. Revenue Decline
Revenue declined by 31.3% from May to June.
2. Volume Decline
Quantity sold declined by 28.3%.
3. Profitability Decline
Net profit declined by 35.1%.
4. Expense Pressure
Expense ratio increased from 5.4% to 6.4%.
5. Supplier Cost Opportunity
Supplier cost variance reached approximately ₦3.3M.
6. Potential Procurement Savings
Approximately ₦1.15M in potential savings was identified through comparable supplier price analysis.
7. Inventory Risk
M005 had approximately ₦4.83M tied up in inventory.
8. Profitability Opportunity
M006 generated approximately 21% of total profit while contributing only 9% of revenue.

## Business Recommendations
Based on the analysis, management should consider:
1. Investigate the June Revenue Decline
The decline in revenue was accompanied by lower quantity sold, AOV and average selling price.
2. Review Product Pricing
Identify products with thin margins and determine whether the issue comes from selling price, purchase cost or both.
3. Optimize Supplier Selection
Investigate the ₦1.15M potential savings opportunity while considering quality, specifications, delivery and commercial terms.
4. Reduce Slow-Moving Inventory
Review products such as M005, M020, M002 and M007 to reduce capital tied up in inventory.
5. Improve Inventory Controls
Investigate negative stock balances and improve the recording of purchases, sales and stock movements.
6. Prioritize High-Profit Products
Products such as M006 and M012 should be evaluated for increased inventory availability, marketing attention and supplier optimization.

## Business Solution Impact
The project transforms raw transaction data into an automated decision-support system.
Instead of manually preparing recurring reports, management can refresh the underlying transaction data and monitor:
Sales → Customers → Procurement → Suppliers → Inventory → Profitability → Financial Performance
This creates a centralized view of the business and makes it easier to identify changes, risks and opportunities as new transactions are recorded.

## What This Project Demonstrates
This project demonstrates my ability to:
•	Clean and transform business data
•	Build relational data models
•	Develop DAX measures
•	Create automated Power BI dashboards
•	Analyze sales performance
•	Analyze customer behaviour
•	Evaluate supplier performance
•	Perform procurement cost analysis
•	Identify potential cost savings
•	Analyze inventory performance
•	Evaluate product profitability
•	Monitor financial performance
•	Translate data into business recommendations

## Conclusion
This project demonstrates how data analytics can be transformed into a practical business intelligence solution.
By combining automated reporting with sales, customer, procurement, supplier, inventory and financial analysis, the solution provides management with a continuous view of business performance.
The analysis moved from:
“What happened?”
to:
“Why did it happen?”
and finally:
“What should the business do about it?”
The ultimate goal was to build more than a dashboard — it was to create a reusable reporting and decision-support system that helps a business monitor performance, identify risks, uncover opportunities and make better decisions from its data.

## Contact

Open to Data Analyst opportunities.

- Email: deborahjonah06@gmail.com
- LinkedIn: https://www.linkedin.com/in/deborah-jonah-220210327




