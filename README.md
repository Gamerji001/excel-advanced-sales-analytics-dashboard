#  Advanced E-Commerce Sales & Profitability Dashboard (Excel)

An interactive, executive-level business intelligence dashboard built entirely in Microsoft Excel. This project processes raw, unstructured sales logs, cleans and structures relational data, and delivers deep insights into regional revenue, channel performance, and product profitability.

---

##  Key Highlights & Technical Stack
* **Data Cleaning & Preprocessing:** Handled messy strings, removed hidden non-printable characters (`CLEAN`, `TRIM`, `PROPER`), and split multi-value columns (`TEXTSPLIT`).
* **Relational Lookups & Error Handling:** Connected sales transactions with the product master repository using `XLOOKUP`, `VLOOKUP`, and `INDEX-MATCH`, backed by `IFERROR` safeguards.
* **Advanced Metrics & Conditional Logic:** Engineered calculated fields for Net Sales, Cost of Goods Sold (COGS), and Profit Margins, alongside tiered customer prioritization using `IFS` and `AND` logic.
* **Interactive Data Modeling:** Built dynamic Pivot Tables, calculated fields, multi-connected **Slicers** (Region, Category, Channel), and an interactive **Date Timeline**.
* **Visual Reporting:** Designed a professional executive dashboard layout featuring a Combo Chart (Revenue vs. Profit) and regional performance breakdowns without visual clutter.

---


## 📂 Project Structure
```text
📦 excel-advanced-sales-analytics-dashboard
┣ 📂 screenshots -- (<img width="1173" height="523" alt="Screenshot 2026-11-17 085126" src="https://github.com/user-attachments/assets/dc2ce27b-3591-462e-aa52-796a1911a8b5" />
)
┃ ┣ 📜 dashboard_overview.png
┃ ┣ 📜 interactive_slicers.png
┗ 📜 Excel_Data_Analyst_Revision_Dataset.xlsx
