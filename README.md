# ☕ Excel-Based Café Sales Insights

This project is an end-to-end Excel-based solution for transforming raw café transaction data into actionable business intelligence. It includes comprehensive data cleaning, transformation, analysis, and dashboard creation using Microsoft Excel.

---

## 🧹 Data Cleaning & Transformation

The original dataset included missing values, inconsistencies, and formatting issues. The following steps were taken to clean and standardize the data:

- **Item Names:** Cleaned using `TRIM` and `PROPER`, invalid or missing values marked as "Missing".
- **Quantity & Price Per Unit:** Standardized and validated for consistency.
- **Total Spent:** Recalculated using formulas to validate correctness (`Cleaned Quantity * Cleaned Price`).
- **Payment Method & Location:** Cleaned using conditional formulas, unknowns standardized as "Missing".
- **Dates:** Parsed into `Month` and `Weekday` for better time-series analysis.
- **Review Flags:** Added logical validation columns to flag inconsistencies in Total Spent or data quality.

---

## 📈 Pivot Tables & Summary Statistics

Key pivot tables created:

- **Total Spend by Cleaned Item**
- **Monthly Spend Trends**
- **Spend by Payment Method**
- **Spend by Location**
- **Transaction Volume by Weekday**

Summary statistics calculated:

- Total Transactions
- Total Revenue
- Average Spend per Transaction
- Median Spend
- Max & Min Spend

---

## 📊 Dashboard Design

An interactive dashboard was built within Excel that includes:

- **KPI Cards:** Showing key metrics
- **Slicers:** For Month, Weekday, Item, Payment Method
- **Charts:** Visual representation of spending trends and distribution

---
## 🛠 Tools Used

- Microsoft Excel (Power Query, Formulas, Pivot Tables, Charts)
- Excel Functions: `IF`, `OR`, `ISERROR`, `VLOOKUP`, `XLOOKUP`, `TRIM`, `PROPER`, `ROUND`, `Data Modeling`

---

## ✍️ Author

**Akhil**  
Graduate Student | Data Analyst  

---

## 📄 License

This project is intended for educational and portfolio use only.
"""
