# Decathlon Sales & Customer Analytics Dashboard (Excel)

## Project Overview
This project explores Decathlon sales and customer data using Microsoft Excel. It presents key performance indicators, product and sports-category performance, annual sales trends, and customer-retention patterns in an interactive dashboard.

The goal is to turn transaction-level data into clear business insights that can support sales monitoring and decision-making.

## Business Questions
- What are the overall sales, order, customer, and average-order-value figures?
- Which sports and product categories contribute most to sales?
- How has sales performance changed from 2024 to 2026?
- Which categories contributed most to the 2026 sales decline?
- What does the customer-retention trend look like?
- How can results be explored by year, gender, and product category?

## Dataset
The workbook includes a transaction-level dataset with **30,000 records** and fields covering:

- **Orders and dates:** Order ID, order date, order time, quarter, month, year
- **Customers:** Customer ID, customer name, gender, age, age group, city, state
- **Products:** Product ID, product name, product category, brand, sport type
- **Sales and profitability:** Quantity, unit price, discount, sales amount, final amount, cost price, profit
- **Operations:** Store, sales channel, payment method, salesperson, delivery type, delivery days
- **Customer experience:** Customer rating, return status, return reason, promotion campaign
- **Customer segments:** Membership type and customer segment

The workbook contains supporting sheets as well as the main data, an insights sheet, a sports image table, and a dashboard.

## Dashboard Highlights
The dashboard reports the following headline metrics and observations:

- **Total sales:** ₹36.7 Cr
- **Total orders:** 30,000
- **Total customers:** 30,000
- **Average order value:** ₹12,236
- **Top sports types shown:** Cycling, Outdoor, Hiking, Gym, and Running
- **Annual sales shown:** ₹13.0 Cr in 2024, ₹13.1 Cr in 2025, and ₹10.6 Cr in 2026
- **2026 sales change:** A decline of approximately **18.88% year over year** (₹2.47 Cr), as stated in the dashboard
- **Main contributors to the decline:** Cycling and Camping together contributed 59.8% of the decline; Cycling alone contributed 37.6%
- **Category concentration:** The dashboard states that the top five categories drove approximately 83% of the total decline

These are figures displayed in the dashboard and have not been independently audited. The 2026 period may not represent a complete calendar year, so comparisons should be interpreted in the context of the data available.

## Tools and Excel Features
- Microsoft Excel
- Interactive dashboard and slicers/filters
- KPI cards and charts
- Sales trend and category comparisons
- Customer-retention visualization

## How to Use
1. Download or clone this repository.
2. Open `Decathlon Dataset.xlsx` in Microsoft Excel.
3. Go to the **Dashboard** sheet to explore the visual report.
4. Use the available filters for year, gender, and product category to investigate different segments.
5. Review the **Data** and **Insights** sheets for the underlying records and supporting analysis.

> For the best experience, open the workbook in a desktop version of Excel that supports the workbook's interactive controls.

## Suggested Repository Structure
```text
decathlon-sales-analytics/
├── README.md
├── Decathlon Dataset.xlsx
└── screenshots/
    └── dashboard.png
```

## Key Takeaway
The dashboard highlights a notable reduction in reported sales in 2026 compared with 2025 and points to Cycling and Camping as major contributors. It also provides a category-level view of sales and a customer-retention trend to help guide further investigation.

## Notes
- This is a portfolio analytics project built around the supplied Excel workbook.
- Confirm formulas, date coverage, and metric definitions before using the figures for operational or financial decisions.
- If the dataset is synthetic or anonymized, label it clearly when publishing the project.

## Author
Add your name, LinkedIn profile, and contact details here.
