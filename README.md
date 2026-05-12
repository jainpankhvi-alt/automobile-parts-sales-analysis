# B2B Sales Analytics Dashboard Project

##  Project Overview
This project analyzes a B2B automobile parts business dataset to generate insights on sales performance, customer behavior, and operational efficiency.

The workflow includes:
- Exploratory Data Analysis (EDA)
- Data Cleaning (Power Query)
- Data Modeling (Power Pivot)
- Dashboard Creation ( Excel)

---

##  Dataset Description

The dataset consists of the following tables:

- Customers (122 records)
- Orders (326 records)
- Order Details (999 records)
- Products (110 records)
- Product Lines (9 records)
- Payments (273 records)
- Employees (24 records)
- Offices (7 records)

---

## 🔗 Data Model Relationships

- Customers → Orders → Order Details
- Products → Order Details
- Customers → Payments
- Employees → Customers
- Offices → Employees

---

##  Data Processing Steps

### 1. Data Cleaning (Power Query)
- Standardized location data (state/country)
- Handled missing values
- Created derived columns:
  - Revenue
  - Shipping Delay
  - Customer Metrics

---

### 2. Feature Engineering

#### Customer-Level
- Total Orders
- Total Revenue
- Average Order Value
- Customer Segmentation

#### Order-Level
- Revenue
- Estimated Profit
- Shipping Delay

---

### 3. Data Modeling (Power Pivot)
- Star schema design
- Fact table: Order Details
- Dimension tables:
  - Customers
  - Products
  - Employees
  - Offices

---

##  Dashboards

### 1.  executive Sales Dashboard

<img width="794" height="486" alt="EXECUTIVE SALES DASHBOARD " src="https://github.com/user-attachments/assets/60228bd6-a224-4586-8f06-782b578c30c6" />

- Total Revenue
- Best / Least Selling Products
- Revenue Trends

### 2. Customer behaviour  Dashboard

<img width="794" height="482" alt="CUSTOMER BEHAVIOUR DASHBOARD" src="https://github.com/user-attachments/assets/e178b930-0815-4c20-9be1-dfce03e28650" />

- Customer Segmentation
- Frequent Buyers
- Customer Lifetime Value



### 3. Salesperson person  Dashboard

<img width="836" height="484" alt="SALESPERSON PERFORMANCE DASHBOARD" src="https://github.com/user-attachments/assets/34da173a-8e48-404d-9c17-31bbf6c29c9e" />

- Sales by Employee
- Customer Portfolio
- Follow-up Insights

---

##  Key Metrics

- Total Revenue
- Total Profit (Estimated)
- Average Order Value
- Customer Retention
- Shipping Delay

---

##  Limitations

- Static dataset (2003–2005)
- No direct cost/profit data
- Missing customer contact details
- Payments not linked to specific orders

---

##  Future Improvements

- Integrate real-time data
- Add customer contact & marketing data
- Implement churn prediction model
- Enhance profit calculation with actual costs

---

##  Tools Used

- Power Query (ETL)
- Power Pivot (Data Modeling)
-  Excel (Dashboarding)

---

##  Conclusion

This project demonstrates how raw transactional data can be transformed into actionable business insights using structured analytics workflows and dashboarding techniques.
