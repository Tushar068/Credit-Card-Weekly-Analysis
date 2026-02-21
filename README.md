#  📊 Credit Card Weekly Analysis
I have designed a two-page interactive Power BI dashboard to monitor weekly credit card revenue, transactions and customer behavior to support strategic business decisions.
## 🔎 Overview  
Every week, the business experiences fluctuations in credit card revenue and transaction volumes. Understanding the drivers behind these changes is critical for sustainable growth.  

This project delivers a two-page interactive Power BI dashboard that analyzes weekly transaction performance and customer behavior. The dashboard helps identify revenue trends, high-value customer segments, demographic patterns and spending behaviors contributing to overall business performance.

## 🎯 Problem Statement  
The organization needs clear visibility into weekly credit card performance to answer key business questions:  

- Are we achieving consistent week-over-week revenue growth?  
- Which customer segments are driving the majority of revenue?  
- Which customer groups require closer monitoring or targeted strategies?  
- How do demographic, income, job type, and card categories influence revenue and utilization?  

The objective of this project is to transform raw transactional and customer data into actionable insights that enable data-driven targeting, performance monitoring, and strategic planning.

## 🗂️ Dataset
The analysis is based on the following datasets:
- [`credit_card.csv`](data/credit_card.csv)
  Contains weekly credit card transaction data including transaction amount, interest earned, expenditure type, card category, average utilization ratio and related transactional metrics.

- [`customer.csv`](data/customer.csv)
  Contains customer demographic and financial attributes including age group, gender, income group, job type, education level and credit limit.

## ⚙️ Methods  

### Data Cleaning and Preparation  
- Removed inconsistencies and handled missing values  
- Standardized categorical fields such as job type, card category, education level, and expenditure type  
- Created calculated columns and DAX measures for revenue, interest, utilization ratio, and growth metrics  
- Ensured correct data types and formatting for accurate aggregation  

### Data Modeling  
- Established relationships between transaction and customer datasets  
- Implemented one-to-many relationships for optimized performance  
- Designed a structured data model (star schema approach)
- Created a calculated dimension table for state mapping to standardize state codes and enable accurate state-level analysis 
- Developed DAX measures for KPIs including Total Revenue, Total Interest, Transaction Count, Average Spend, and Week-over-Week Growth  

### Analysis and Visualization  
- Built two dedicated report pages: Transaction Report and Customer Report  
- Implemented KPI cards for high-level performance tracking  
- Designed interactive charts with slicers and drill-down capabilities  
- Enabled week-level comparison for trend and growth analysis  

## 🛠️ Tools and Technologies  
- Power BI (Data Modeling, DAX, Interactive Dashboards)  
- DAX (Data Analysis Expressions)  
- Microsoft Excel (Initial data processing)  

## 📌 Key Insights (KPIs)  

### Transaction Metrics  
- Total Revenue: 55.32M  
- Total Interest: 7.84M  
- Total Transactions: 656K  
- Best Performing Week Identification  
- Week-over-Week Growth %  

### Customer Metrics  
- Total Customers: 10.11K  
- Average Customer Income  
- Average Credit Limit  
- Average Credit Utilization Ratio (27.49%)  
- Customer Satisfaction Score (CSS)  

## 📈 Dashboard  



This project contains two report pages:

### 1️⃣ Transaction Report  

Visualizations Included:  
- KPI Cards (Revenue, Interest, Transactions, Best Week)  
- Quarterly Revenue & Transaction Trend (Column + Line Chart)  
- Revenue by Customer Job (Bar Chart)  
- Revenue by Expenditure Type (Bar Chart)  
- Revenue by Card Category (Bar Chart)  
- Revenue by Education Level (Funnel Chart)  
- Weekly Revenue Table with WoW Growth  

### 2️⃣ Customer Report  

Visualizations Included:  
- KPI Cards (Customers, Avg Income, Avg Credit Limit, Utilization Ratio, CSS)  
- Average Spend by Age & Gender (Clustered Bar Chart)  
- Average Spend by Income Group & Gender (Bar Chart)  
- Customer Count by Gender (Donut Chart)  
- Credit Utilization vs Credit Limit (Bubble Chart)  
- Customer Count by Age Group (Column Chart)  
- Card Type-wise Customer Distribution and Income (Matrix Table)  

## ✅ Results and Conclusion  
The dashboard provides a centralized and structured view of weekly credit card performance and customer behavior.  

Key outcomes include:  

- Clear visibility into week-over-week revenue growth patterns  
- Identification of high-performing customer segments (by income, job type, card type, and education level)  
- Insight into spending behavior across age groups and genders  
- Understanding of credit utilization trends relative to credit limits  
- Data-backed support for customer targeting and monitoring strategies  

This project demonstrates strong capabilities in data modeling, DAX measure development, KPI tracking, and business-oriented dashboard design using Power BI.

## 📁 Repository Content  
- [`Credit Card Weekly Analysis.pbix`](Credit_Card_Weekly_Analysis.pbix) – Power BI Dashboard File  
- `data`– Raw and processed datasets  
- `assets/` – Dashboard (Transaction Report & Customer Report)  
- `README.md` – Project documentation  
