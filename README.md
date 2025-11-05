<img width="1439" height="811" alt="retail_sales_dashboard" src="https://github.com/user-attachments/assets/db9b494f-e27a-4fbc-902b-99759f59f4e6" /># Cosmetics Retail Analytics Dashboard  
**Power BI | Pure Power Query ETL | DAX | Star Schema DW**

This project showcases an end-to-end BI solution for a cosmetics retail business.  
All data extraction, transformation, and modeling were done **100% inside Power BI** using:

 Power Query (M) for ETL  
 Star schema data warehouse modeling  
 DAX for KPIs, ranking, segmentation  
 Drill-through analytics & slicers  

> **No Python / SQL / external ETL tools used.**

---

## Dashboards Overview

### Retail Sales & Promotion Dashboard
- Total Sales, Orders, AOV, Discount Rate
- Monthly trend & YoY comparison capability
- Top-N store ranking & dynamic filters
- Category contribution analysis
- Promotion effectiveness (discount vs gift sets)

### Customer Loyalty & Segmentation Dashboard
- Member vs Non-member spending insight
- Loyalty tiers (Silver | Gold | Platinum)
- AOV by customer group
- Category spend by member tier
- Customer contribution to revenue

---

## Tech Stack
| Component | Tools |
|---|---|
ETL | **Power Query (M)**  
Modeling | **Star Schema (Fact + Dimension)**  
Metrics | **DAX measures**  
Visualization | **Power BI Desktop**  
Data Source | OLTP CSV files (mock retail dataset)**  

---

## Project Structure

```
 Dataset/OLTP/
   ├─ Customer.csv
   ├─ Product.csv
   ├─ Promotion.csv
   ├─ SalesDetail.csv
   └─ SalesTransaction.csv

 Screenshots/
   ├─ retail_sales_dashboard.png
   └─ customer_insight_dashboard.png

ETL & Dashboard.pbix
README.md
```

---

## Key Highlights

- Built BI solution from raw OLTP data to interactive dashboards  
- Designed **Fact + Dimension schema** with surrogate keys  
- Implemented **full ETL in Power Query**  
- Created **analytical DAX measures** for financial KPIs & segmentation  
- Delivered business insights for:
  - Store performance
  - Customer loyalty programs
  - Promotion strategies
  - Product category sales  
- Demonstrates **Business + Data Analytics + BI Engineering skills**

---

## Screenshot Preview

| Sales & Promotion Dashboard | Customer Loyalty Dashboard |
|----------------------------|-----------------------------|
| ![<img width="1439" height="811" alt="retail_sales_dashboard" src="https://github.com/user-attachments/assets/956653a2-df6b-43a6-9747-14a4c72fed9a" />
]![Uploading retail_sales_dashboard.png…]()
(screenshots/retail_sales_dashboard.png) | ![<img width="1435" height="803" alt="customer_insight_dashboard" src="https://github.com/user-attachments/assets/0612db53-6082-43e4-8cfb-7f5da2a7a4e1" />
](screenshots/customer_insight_dashboard.png) |

---

### Insights Highlight
- Members contributed **~60%+** of total revenue  
- Skincare was the highest-selling category  
- Percentage discount promos drove higher discount per bill than gift promos  
- Loyalty members had higher AOV vs non-members  

---

### About this Project
Created as part of a portfolio to demonstrate:

- Business understanding  
- Data modeling & BI design  
- Analytics storytelling  
- Power BI technical execution  

---
