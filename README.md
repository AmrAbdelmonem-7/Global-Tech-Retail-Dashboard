# Global Tech Retail Analytics Dashboard (2024–2025)

End-to-end Business Intelligence project built using Power BI, Power Query, Star Schema modeling, and DAX measures.

## 📊 Project Overview
- **Dataset:** Global Tech Retail (2024–2025 transactions)
- **Architecture:** Star Schema (`FactSales`, `DimCustomer`, `DimProduct`, `DimSalesRep`, `DimDate`)
- **Theme:** Clean Executive Royal Blue

## 🛠️ Key Components
1. **Data Cleaning & Staging (Power Query):** Handled missing values, standardized text data, formatted dates, and removed duplicates/invalid rows.
2. **Data Modeling:** Built a robust Star Schema with active and inactive relationships (supporting multi-date analysis like `OrderDate` vs `ShipDate`).
3. **Advanced DAX Measures:**
   - `Total Sales`, `Total Profit`, `Profit Margin %`, `Total Orders`
   - Time Intelligence / Bonus: `Sales PY`, `YoY Sales Growth %`, and `Sales by ShipDate` (using `USERELATIONSHIP`).
4. **Interactive Dashboard:** Designed following the "Describe, Compare, Diagnose" storytelling framework with dynamic filtering.
