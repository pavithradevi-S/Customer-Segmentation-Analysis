# Customer Segmentation Dashboard using Power BI

## Project Overview
This project focuses on customer segmentation using Power BI to analyze customer behavior, spending patterns, revenue contribution, and churn trends.

The dashboard helps businesses identify valuable customer groups and make data-driven decisions for customer retention and targeted marketing.

---

## Objective
The main objective of this project is to segment customers based on:

- Customer behavior
- Spending patterns
- Monthly charges
- Revenue contribution
- Customer churn
- Customer tenure

---

## Tools & Technologies Used

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Visualization
- Customer Analytics

---

## Dataset
**Dataset Used:** Telco Customer Churn Dataset

### Features Included:
- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Monthly Charges
- Total Charges
- Contract Type
- Payment Method
- Internet Service
- Churn

---

## Data Cleaning Process
Data preprocessing was performed using Power Query:

- Removed missing values
- Converted incorrect data types
- Removed unnecessary columns
- Fixed TotalCharges errors
- Cleaned customer records

---

## Customer Metrics Created

### Total Customers
```DAX
Total Customers = COUNTROWS(Customer_Segmentation)
