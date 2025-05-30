# IMDb-DataExplorer
A data-driven exploration of movie insights using SQL and the IMDb database.

This project was built in Jupyter using PostgreSQL to perform exploratory data analysis, data cleaning, transformation, and aggregation on a sample of the IMDb dataset. The goal was to extract meaningful insights from raw data such as MPAA ratings, box office revenue, movie budgets, and actor roles.

---

## 🧠 Key Objectives

- Learn to query relational data using SQL
- Clean unstructured fields (like budget and ratings) using regex and string functions
- Join multiple tables to derive new insights (e.g. movie profit)
- Analyze actor role frequencies and film earnings distributions

---

## 📊 What This Project Includes

- Data cleaning and regex-based parsing of MPAA ratings and gross earnings
- Creation of SQL views to isolate high-grossing and high-budget films
- Subqueries and joins to calculate movie profitability
- Summary statistics using `PERCENTILE_CONT()` for earnings distributions
- Role-based aggregation of actor appearances

---

## 🧰 Tools & Technologies

- **PostgreSQL**: SQL engine
- **Jupyter Notebook**: Interactive development
- **JupySQL**: Run SQL inside notebooks
- **Pandas & NumPy**: For small data handling
- **Regex & String Functions**: For parsing `info` fields

---

## 💡 Sample Insights

- 🎬 **Highest Grossing Film**: *Avatar* ($760M in U.S. gross)
- 💰 **Most Expensive Film**: *Pirates of the Caribbean: At World's End* ($300M budget)
- 🧠 **Top Actor (by roles)**: *Bob Barker* (6,853 roles)
- 📉 **Skewed Distribution**: A small number of films earn the majority of box office revenue

---
