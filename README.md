# Real Estate Data Analysis in Excel

**Author**: Moid Ahmed  
**Tool Used**: Microsoft Excel  
**Skills Applied**: Data Cleaning, PivotTables, VLOOKUP, Data Analysis, Helper Columns
**Dataset**: https://www.kaggle.com/datasets/omniamahmoudsaeed/real-estate-sales-2001-2022
---

## 📊 Project Overview

This project involved cleaning and analyzing a dataset containing real estate transactions with attributes like Serial Number, Address, Assessed Value, Sale Amount, Property Type, Residential Type, Latitude, Longitude, and Historical Year (H.Year). The goal was to derive meaningful insights using Excel, primarily through **PivotTables** and **VLOOKUP**.

---

## 🧼 Data Cleaning Steps

- Formatted columns for consistency and readability.
- Split Longitude and Latitude values from combined format into separate columns.
- Created a Helper Year column based on the `Date Recorded` or `List Year`.
- Filled in missing values for critical columns where possible.
- Ensured all data types were correctly set (e.g., numbers, dates, text).
- Removed or flagged clearly invalid data (e.g., out-of-range values).

---

## ✅ Questions Solved in Excel

### 1. Sales Analysis
- What is the total Sale Amount by each Town?
- How does the average Assessed Value vary by Property Type?
- What is the Sales Ratio trend by List Year?

### 2. Property Type Insights
- How many properties are there in each Residential Type?
- What is the average Sale Amount per Residential Type?
- Which Property Type has the highest total Sale Amount?

### 3. Time-Based Trends
- How many sales were recorded each year? (Group by List Year or Date Recorded)
- What is the yearly average Sales Ratio?

### 4. Location-Based Analysis
- What is the total Sale Amount by Town?
- Which towns have the highest average Assessed Value?
- Grouped properties by geographic location using Latitude and Longitude.

### 5. Lookup-Based Questions
- Used `VLOOKUP` to find Sale Amount, Assessed Value, or other information for a given Serial Number:
  
    =VLOOKUP(serial_number, Table1, col_index, FALSE)

### 6. Historical Year (H.Year) Analysis
- How many properties were built in each H.Year category?
- What is the average Assessed Value for properties grouped by H.Year?

### 7. Cross-Analysis
- Compared Sale Amount vs Assessed Value by Town or Property Type using PivotTables.
- Created dynamic summaries of Sale Amount grouped by both Town and Residential Type.

---

## 📌 Notes

- All analysis was performed using built-in Excel features without external plugins.
- PivotTables were used extensively for grouping, aggregating, and visualizing data trends.
- VLOOKUP was used for fast record-based lookups, enabling quick user-specific queries.

---

## 💼 Skills Demonstrated

- Excel formulas (VLOOKUP, IFERROR, LEN, TRIM)
- PivotTables and PivotCharts
- Data transformation and preparation
- Analytical reasoning and trend discovery
- Geo-based grouping (using towns and coordinates)

---

## 📧 Contact

**Moid Ahmed**  
LinkedIn: www.linkedin.com/in/ask-moidahmed
