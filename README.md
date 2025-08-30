# Ireland-crime-analysis-
"Crime Data Analysis of Ireland Using Excel(CSO Dataset)"
This project analyses **recorded crime incidents in Ireland** using data from the Central Statistics Office (CSO).  
The analysis has been performed in **Microsoft Excel** with formulas, pivot tables, and structured sheets.  

---

##  Repository Structure
ireland-crime-analysis
┣ data
┃ ┗ CJQ06_raw.csv
┣  analysis
┃ ┗ Master sheet of crime in ireland.xlsx
┣ README.md

---

##  Tools Used
- Microsoft Excel (Formulas, Filters, Pivot Tables)
- Dataset: Central Statistics Office (Ireland, 2003–2025)

---

##  Basic Analysis (Excel Formulas & Filters)

| Q.No | Question | Method Used | Final Answer |
|------|-----------|-------------|--------------|
| 1 | Total number of crime incidents overall | `=SUM(VALUE)` | **10,327,313** |
| 2 | First & last year-quarter available | Direct observation (dataset sorted) | **2003Q1 – 2025Q1** |
| 3 | Total crimes in 2003Q1 | `=SUMIFS(Quarter="2003Q1")` | **112,176** |
| 4 | Highest incidents Garda Division | Pivot (Division vs VALUE) | **D.M.R. North Central Garda Division** |
| 5 | Most common offence type | Pivot (Offence vs VALUE) | **Theft and related offences** |
| 6 | Murder in Dublin Division (2005) | Pivot (Quarter=2005, Type=Murder, Divisions=DMR Eastern/Western/North Central/Northern/South Central/Southern) | **26** |

> These 6 questions were solved in Excel **without charts**, focusing on formulas and pivot basics.  
> Charts and advanced analysis will be added in the next stage.

---

## 📌 Next Steps
- 📈 Intermediate Analysis → Yearly trends, Top 5 offences, Sexual offences 2010–2020 trend  
- 🔎 Advanced Analysis → Dublin vs Non-Dublin, Covid period impact, Forecast for 2026  

---

📍 **Author:** Unnati Bhardwaj  
📍 **LinkedIn:** www.linkedin.com/in/unnati-bhardwaj-0b1554289  
📍 **GitHub:**   https://github.com/BhardwajUnnati
