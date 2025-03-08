# Power_BI_Dashboard_for_BI-360

## **Project Summary: Business Insights 360 Project Report for AtliQ Hardwares**

## **Overview**
AtliQ Hardware has experienced rapid growth and aims to leverage Power BI for data-driven decision-making. This project provides insights into **Finance, Sales, Marketing, and Supply Chain** to address stakeholder queries effectively.

## **Technology Stack**
- **SQL**  
- **Power BI Desktop & Power BI Service**  
- **Excel**  
- **DAX Language & DAX Studio (for optimization)**  
- **Project Charter File**  

## **Key Learnings from Power BI**
- Asking key questions before project initiation.  
- Creating calculated columns & measures using DAX.  
- Data modeling best practices (Snowflake Data Modeling).  
- Implementing bookmarks and buttons for navigation.  
- Using the DIVIDE function to prevent division errors.  
- Creating a date table with M language for time intelligence.  
- Dynamic titles based on applied filters.  
- KPI indicators and conditional formatting in visuals.  
- Data validation for accurate reporting.  
- Publishing reports to Power BI Services and setting up auto-refresh.  
- Creating a Power BI App and managing access via workspaces.  

## **Business Metrics and Concepts**
- **Financial Metrics**: Gross Price, Pre-invoice Deductions, Post-Invoice Deductions, Net Invoice Sale, Gross Margin, Net Sales, Net Profit.  
- **Accounting & Operations**: COGS (Cost of Goods Sold), YTD (Year to Date), YTG (Year to Go).  
- **Sales Channels**: Retailers, Direct Sales, Distributors, Consumers.  

## **Company Insights**
AtliQ Hardware expanded rapidly but suffered losses due to **intuition-based decisions**, especially in the U.S. market. Competitors used analytics for strategic decisions, prompting AtliQ to build an **analytics team** for better business insights.

## **Project Planning and Execution**
### **Key aspects discussed:**
- Dashboard objectives & success metrics.  
- Project timeline and deadlines.  
- Stakeholder expectations, fears, and risks.  
- Required data and resources for dashboard development.  
- Dashboard design and user needs.  

## **Dataset Breakdown**
The dataset is sourced from a **MySQL database** and includes:
- **Dimension Tables**: Static data such as customers, products, and markets.  
- **Fact Tables**: Transactional data such as sales, forecasting, and costs.  

## **Key Tables and Purpose**
- **dim_customer** – Customer details across 27 markets and two platforms (Brick & Mortar, E-commerce).  
- **dim_market** – Market details across 27 markets, 7 sub-zones, and 4 regions.  
- **dim_product** – Product data across divisions (Peripherals, PC, Networking).  
- **fact_forecast_monthly** – Forecasting customer demand for optimization.  
- **fact_sales_monthly** – Actual sales data for comparison.  
- **freight_cost, gross_price, manufacturing_cost** – Various cost-related data.  
- **pre_invoice_deductions & post_invoice_deductions** – Discount and additional cost details.

## **Data Modeling**
- **Method Used**: Snowflake Data Modeling.  
- Ensures **efficient and scalable Power BI reports**.  

## **Dashboard Design – Key Views**
1. **Home View** – Central navigation hub for all reports.  
2. **Finance View** – Key financial metrics and performance.  
3. **Sales View** – Sales insights by market and channel.  
4. **Marketing View** – KPI tracking and campaign performance.  
5. **Supply Chain View** – Inventory and logistics insights.  
6. **Executive View** – High-level business summary for decision-makers.  
7. **Support** – Additional resources and assistance.  

## **Project Outcome & Impact**
- Enabled AtliQ Hardware to **transition from intuition-based to data-driven decision-making**.  
- Improved **financial planning, sales forecasting, marketing efficiency, and supply chain optimization**.  
- Provided executives and stakeholders with **real-time insights** for better strategic planning.
