# Loan-Data-Analysis
# 📊 USA Loan Analysis Report — Power BI Dashboard




A comprehensive, multi-page **usa loan analytics dashboard** built in Power BI, designed to give financial analysts and stakeholders deep visibility into loan portfolio performance, borrower risk, and funding trends — all in one interactive report.

---

## 📈 Key Metrics

| Metric | Value |
|---|---|
| Total Loan Applications | 38.6K |
| Total Funded Amount | $435.8M |
| Total Amount Received | $473.1M |
| Avg Interest Rate | 12.0% |
| Good Loans | 86.2% |
| Bad Loans | 13.8% |

---

## 📁 Report Pages

### 1 — Summary
High-level KPI cards with MoM and MTD comparisons. Good vs. bad loan breakdown with donut charts and a detailed loan status table (Fully Paid, Charged Off, Current).

### 2 — Overview
Trend analysis across dimensions: funded amount by month, US state-level choropleth map, loan term distribution, employment length, purpose breakdown, and home ownership segmentation.

### 3 — Details
Granular loan-level table with drill-down by Loan ID, purpose, home ownership, grade, sub-grade, issue date, funded amount, interest rate, installment, and amount received.

---

## 🛠 Tools & Skills

- **Power BI Desktop** — data modelling, DAX measures, report design
- **DAX** — custom KPIs, MTD/MoM calculations, good vs. bad loan logic
- **SQL** — data extraction and validation from source database
- **Data Visualisation** — donut charts, line graphs, filled maps, bar charts, matrix tables
- **Interactive slicers** — filter by State, Grade, Purpose, and Loan Quality

---

## 💡 Key Insights

- Loan applications grew **6.9% MoM**, signalling strong demand momentum
- **Debt consolidation** dominates loan purpose at $232.46M funded
- Borrowers with **10+ years** of employment account for the highest funded amount ($116.12M)
- **60-month term** loans (62.66%) significantly outpace 36-month loans in volume
- Mortgage holders represent the largest home ownership segment by funded amount ($219.33M)

---

## 📂 Files

├── [Power BI Report](https://github.com/abhisheknirmal02-lab/Loan-Data-Analysis/blob/main/USA%20LOAN%20ANALYSIS.pbix)
├── [SQL Query ](https://github.com/abhisheknirmal02-lab/Loan-Data-Analysis/blob/main/US%20LOAN%20project%20sql%20query.docx)
├── [Loan Data]()
├── [DAX Codes](https://github.com/abhisheknirmal02-lab/Loan-Data-Analysis/blob/main/DAX%20code%20Loan%20Project.xlsx)
├── [Dashboard Preview](https://github.com/abhisheknirmal02-lab/Loan-Data-Analysis/blob/main/Summary.png)


---

## 🚀 How to Use

1. Clone this repository
2. Open `usa_loan_analysis_report.pbix` in Power BI Desktop
3. Connect to your data source or use the included CSV
4. Refresh the dataset and explore all three report pages

---

*Built as a portfolio project to demonstrate end-to-end data analytics — from SQL extraction to interactive Power BI storytelling. ⭐ Star this repo if you find it useful!*
