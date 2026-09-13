📊 Sales & Employee Performance Analysis | Power BI
📊 Project Overview

This project is an interactive Power BI data analytics project designed to analyze sales performance, order details, product information, customer behavior, supplier data, and employee performance.

The project combines multiple business datasets into a unified data model to provide meaningful insights into sales operations, product performance, customer activity, and employee KPIs.

The analysis focuses on understanding business performance, identifying trends, and supporting data-driven decision-making through interactive dashboards and visual reports.

🎯 Project Objectives

The main objectives of this project are to:

Analyze overall sales performance and order trends.
Identify top-performing products and product categories.
Analyze product prices, stock levels, and reorder levels.
Evaluate customer purchasing behavior and order activity.
Analyze supplier information and product distribution.
Measure employee performance using KPIs and targets.
Compare employee performance against yearly targets.
Identify trends in revenue, quantities sold, and order values.
Build an interactive dashboard for business performance analysis.
Provide actionable insights to support business decisions.
🗂️ Data Sources

The project uses multiple related datasets containing information about products, sales, customers, suppliers, and employees.

1. Products Data

Contains information about the products available in the business.

Key fields include:

ProductID
ProductName
CategoryID
SupplierID
UnitPrice
UnitsInStock
UnitsOnOrder
ReorderLevel
Discontinued
QuantityPerUnit
2. Categories Data

Contains product category information.

Key fields include:

CategoryID
CategoryName
Description
3. Suppliers Data

Contains information about product suppliers.

Key fields include:

SupplierID
CompanyName
ContactName
ContactTitle
Address
City
Country
Phone
4. Orders Data

Contains information about customer orders.

Key fields include:

OrderID
CustomerID
EmployeeID
OrderDate
RequiredDate
ShipAddress
ShipCity
ShipCountry
OrderTotal
5. Order Details Data

Contains detailed information about products included in each order.

Key fields include:

OrderID
ProductID
Quantity
UnitPrice
Discount
Total
6. Customers Data

Contains customer information used to analyze customer activity and purchasing behavior.

Key fields include:

CustomerID
CompanyName
ContactName
ContactTitle
Address
City
Country
Phone
7. Employees Data

Contains employee information used to analyze employee performance.

Key fields include:

EmployeeID
FirstName
LastName
BirthDate
HireDate
City
Country
Region
PostalCode
8. Employees Targets Data

Contains employee yearly targets and performance-related information.

Key fields include:

EmployeeID
Full Name
2017
2018
Total 2017&2018
9. Employees KPI Data

Contains employee KPI measurements and performance indicators.

Key fields include:

EmpID
Date
Month
Attendance
Average Task Completion Rate
Co-Operation
Over All
Over Time
Percentage
🧹 Data Preparation

The data preparation process included:

Reviewing and understanding the different datasets.
Handling missing values and checking data quality.
Standardizing column names and data formats.
Checking data types for dates, numeric fields, and identifiers.
Removing duplicates where necessary.
Creating calculated columns and measures for analysis.
Merging and connecting related datasets using primary and foreign keys.
Preparing the data for Power BI reporting and visualization.
🏗️ Data Modeling

The project uses a relational data model in Power BI to connect the different business datasets.

Main Relationships
Categories → Products using CategoryID.
Suppliers → Products using SupplierID.
Products → Order_details using ProductID.
Orders → Order_details using OrderID.
Customers → Orders using CustomerID.
Employees → Orders using EmployeeID.
Employees → Employees Targets using EmployeeID.
Employees → Employees KPI using EmployeeID / EmpID.

The model combines sales, product, customer, supplier, and employee information to support cross-functional business analysis.

Data Model Structure

The model includes:

Product and category information.
<img width="869" height="476" alt="Screenshot 2024-10-25 195552" src="https://github.com/user-attachments/assets/2099e252-f4bc-467b-b8f7-806bae7c0778" />

Supplier information.
<img width="892" height="466" alt="Screenshot 2024-10-25 195603" src="https://github.com/user-attachments/assets/7c410d0c-23af-493f-9e27-aee68a1864aa" />

Customer and order information.
<img width="971" height="468" alt="Screenshot 2024-10-25 195627" src="https://github.com/user-attachments/assets/ac566a1c-4109-4e13-8bb2-c6b0d4ae17c5" />

Order-level and product-level sales details.
<img width="944" height="455" alt="Screenshot 2024-10-25 195637" src="https://github.com/user-attachments/assets/c5a0fc67-a5c9-448b-a1ed-2fea7c446552" />

Employee targets.
Employee KPI performance data.

This structure supports interactive filtering, drill-down analysis, and performance comparisons across different business dimensions.

📈 Dashboard

The Power BI dashboard is designed to provide visual insights into sales and employee performance.

Sales Analysis
Total sales and order performance.
Sales trends over time.
Total quantity sold.
Average order value.
Top-performing products.
Sales by product category.
Sales by customer.
Sales by country.
Product & Inventory Analysis
Product prices and stock levels.
Products with low stock.
Reorder level analysis.
Product category performance.
Supplier and product distribution.
Customer Analysis
Customer order activity.
Top customers by sales.
Customer purchasing behavior.
Geographic distribution of customers.
Employee Performance Analysis
Employee KPI performance.
Attendance analysis.
Average task completion rate.
Cooperation scores.
Overtime analysis.
Overall employee performance.
Employee performance compared with yearly targets.
🔍 Key Findings

The project is designed to identify important business insights, including:

Which products and categories generate the highest sales.
Which customers contribute the most to overall revenue.
Which products require inventory attention.
How sales performance changes over time.
Which employees achieve their assigned targets.
How employee KPIs vary across different periods.
Which performance indicators have the greatest impact on overall employee performance.

Actual findings and numerical results can be added after analyzing the Power BI dashboard.

🛠️ Tools & Technologies
Power BI
Power Query
DAX
Data Cleaning
Data Transformation
Data Modeling
Relational Data Model
Data Visualization
Exploratory Data Analysis
KPI Analysis
Business Intelligence
📁 Project Structure
sales-employee-performance-analysis/
│
├── README.md
│
├── PowerBI/
│   └── sales_employee_analysis.pbix
│
├── Screenshots/
│   └── dashboard.png
│
├── Data/
│   └── README.md
│
└── Documentation/
    └── data_model.png
📌 Project Type

Data Analytics | Power BI | Business Intelligence | Data Modeling | Sales Analysis | Employee KPI Analysis
