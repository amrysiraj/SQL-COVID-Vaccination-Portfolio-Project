# COVID-19 Data Exploration with SQL Server

## 📌 Project Overview

This project analyzes global **COVID-19 deaths** and **vaccination** data using **Microsoft SQL Server Management Studio (SSMS)**. The dataset is explored, cleaned, and transformed using SQL, and a reusable SQL view is created for visualization in **Tableau**.

---

## 🛠️ Tools Used

- Microsoft SQL Server
- SQL Server Management Studio (SSMS)
- Tableau

---

## 📚 SQL Concepts Demonstrated

- Joins
- Common Table Expressions (CTEs)
- Temporary Tables
- Window Functions
- Aggregate Functions
- Views
- Data Type Conversion
- Filtering
- Grouping
- Ordering

---

## 📊 Analysis Performed

- Compared total COVID-19 cases vs. total deaths
- Analyzed total cases relative to population
- Identified countries with the highest infection rates
- Identified countries with the highest death counts
- Analyzed continent-level death statistics
- Calculated global COVID-19 statistics
- Computed rolling vaccination totals using window functions
- Calculated the percentage of the population vaccinated

---

## 🔄 Project Workflow

1. Imported the COVID-19 datasets into SQL Server.
2. Explored and analyzed the data using SQL queries.
3. Cleaned and transformed the data for analysis.
4. Created a SQL view (`PercentPopulationVaccinated`) for downstream analysis.
5. Connected Tableau to the SQL Server view to build interactive dashboards and visualizations.

---

## 📁 Repository Contents

```
├── COVID_Data_Exploration.sql
├── README.md
└── LICENSE
```

---

## 📈 Future Improvements

- Build additional Tableau dashboards.
- Add trend analysis by country and continent.
- Include more advanced SQL techniques such as stored procedures and dynamic SQL.

---

## 📄 License

This project is licensed under the MIT License.
