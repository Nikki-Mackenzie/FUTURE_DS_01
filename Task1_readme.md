# Task 1 — E-Commerce Sales Dashboard (2009–2010)

## 📊 Overview
This Power BI dashboard visualizes online retail sales data for 2009–2010, highlighting key business insights such as total sales, customer behavior, and country-level performance.  
The project is part of the **FUTURE_DS_01** repository series focusing on data visualization and storytelling.

---

## 🧠 Data Used
- **Dataset:** Online Retail dataset (2009–2010 subset)
- **Source:** UCI Machine Learning Repository / Excel file
  

---

## 🧹 Data Cleaning & Preprocessing
Steps taken before dashboard creation:
1. Removed cancelled transactions (`InvoiceNo` starting with “C”)
2. Dropped missing or null `CustomerID` entries
3. Created new columns:
   - `TotalSales = Quantity * UnitPrice`
   - Extracted `Year`, `Month`, and `Day` from `InvoiceDate`
4. Filtered data to include only **2009–2010**
5. Verified consistency of country and description fields

---

## 💡 Dashboard Insights
Key takeaways from the Power BI dashboard:
- **Total Orders:** 19.22K | **Total Customers:** 4,314  
- **Top Selling Item:** White Hanging Heart T-Light Holder  
- **Top Country:** United Kingdom (≈ 86% of total sales)
- **Trend:** Noticeable rise in sales during late 2010 (holiday season)
- **Average Order Value (2009):** 55.92
- The UK dominates sales, followed by EIRE and the Netherlands.

---

## 🧭 Files in This Folder
| File | Description |
|------|--------------|
| `E-Commerce Dashboard 2009-2010.pbix` | Power BI dashboard file |
| `README.md` | Documentation for preprocessing, overview, and insights |

---

## 🚀 Next Steps
This is **Task 1** in the **FUTURE_DS_01** repository.  
Future tasks will build upon this analysis to include deeper predictive and statistical insights.
