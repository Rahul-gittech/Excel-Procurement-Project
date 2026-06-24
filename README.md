# Kafe Fajka — Inventory & Sourcing Analysis (Excel)

An Excel portfolio project based on a small hospitality business. It organises product, supplier, inventory and purchasing information into linked worksheets and uses simple analysis to support inventory and sourcing decisions.

## What the workbook includes
- Product and supplier master data
- Inventory snapshots and estimated inventory valuation
- Supplier coverage mapping
- Purchase-order workflow model
- Two PivotTable-style summary sheets:
  - **Pivot Inventory By Category** — estimated stock value by category
  - **Pivot Supplier Coverage** — number of products covered by each supplier
- Assumptions, data quality notes and audit checks

## Analysis approach
PivotTables are the main analysis method in this project. They summarise inventory value by category and supplier coverage by product count. XLOOKUP/IFERROR, SUMIFS and COUNTIFS are included as supporting Excel techniques for lookups and summary checks.

## Data note
This is a portfolio and learning project built from partial real-world context plus management estimates. The workbook labels source type and confidence level so verified records and estimates are not presented as the same thing. Inventory value is an estimated valuation, not audited accounting inventory. Category-level sales are estimates.

## Skills demonstrated
Excel · PivotTables · Inventory Valuation · Supplier Mapping · XLOOKUP · IFERROR · SUMIFS · COUNTIFS · Procurement Logic · Data Quality Documentation

## Files
- `Kafe_Fajka_GitHub_Ready.xlsx` — final workbook
- `PROJECT_GUIDE.md` — explanation of sheets and how to review the project
