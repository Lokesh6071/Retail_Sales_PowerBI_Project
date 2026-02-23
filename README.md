# Retail Sales Analysis – Power BI Project

## Project Overview

This project presents an interactive Retail Sales Analysis dashboard developed using Power BI. The objective of the project is to analyze retail transaction data and generate meaningful business insights using DAX calculations, time intelligence functions, and advanced Power BI features.

The report provides a comprehensive view of sales performance, category contribution, time-based trends, and key influencing factors affecting revenue.

---

## Dataset Information

- Source: Kaggle  
- Type: Retail Store Sales Dataset (Raw and Uncleaned)  
- Key Fields:
  - Transaction Date  
  - Category  
  - Item  
  - Quantity  
  - Price Per Unit  
  - Payment Method  
  - Location  

Data cleaning and transformation were performed using Power Query before building the data model.

---

## Data Modeling

- Created a separate Date table to enable time intelligence calculations  
- Established relationships between Date table and sales table  
- Ensured proper data types and removed inconsistencies  

---

## DAX Measures Implemented

The following DAX measures were created:

- Total Sales (SUMX calculation)
- Average Sales per Transaction
- Performance Classification (Good/Poor)
- Category Contribution Percentage
- Category Ranking (RANKX)
- Product Ranking (RANKX)
- Year-to-Date (YTD) Sales
- Month-over-Month (MoM) Growth
- Latest Year Sales
- Latest Month Sales
- Parameter-based Measure Switch (Sales vs Profit)
- Selected Category Sales vs Overall Sales Comparison

Advanced DAX functions used include:

- CALCULATE
- SUMX
- AVERAGEX
- RANKX
- TOTALYTD
- ALL
- VAR
- DIVIDE

---

## Visualizations Used

The dashboard includes the following visuals:

- Card visuals for KPI display
- Table visual for structured category comparison
- Donut chart for category contribution
- Bar chart for category and item analysis
- Line chart for monthly sales trend
- Drill Through page for detailed category breakdown
- Report Page Tooltips for additional contextual insights

---

## Advanced Power BI Features Implemented

- Drill Through functionality for detailed category-level analysis
- Bookmarks for interactive view switching
- Sync Slicers across report pages
- Field Parameters for dynamic measure switching
- Report Page Tooltips for enhanced interactivity
- AI Visuals:
  - Key Influencers
  - Decomposition Tree

---

## Key Insights

- Quantity has a significant impact on total sales.
- Certain categories contribute a higher percentage to overall revenue.
- Monthly trend analysis highlights fluctuations in sales performance.
- AI visuals identify major factors influencing sales growth.

---

## Tools and Technologies Used

- Power BI Desktop
- DAX (Data Analysis Expressions)
- Power Query
- GitHub for version control

---

## Conclusion

This project demonstrates the ability to perform data modeling, implement advanced DAX calculations, apply time intelligence functions, and design an interactive business intelligence dashboard. The report supports data-driven decision-making through structured analysis and dynamic visual reporting.
