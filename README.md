# SpaceX Launch Data — SQL Analysis

A SQL-focused notebook exploring historical SpaceX launch records through queries, filtering, and aggregation.

This project demonstrates how relational querying can be used to answer questions about launch activity, payloads, and mission outcomes.

## Questions Explored

- Which launch sites appear in the dataset?
- How many missions were recorded?
- How do payload masses vary?
- What outcomes are associated with different launch records?
- How can dates, launch sites, and booster versions be used to filter the data?

## Tools

- SQL
- SQLite
- Jupyter Notebook
- ipython-sql
- Python

## SQL Techniques

- `SELECT`, `DISTINCT`, `WHERE`, and `LIKE`
- `GROUP BY` and `ORDER BY`
- `COUNT()`, `SUM()`, `AVG()`, and `MIN()`
- Subqueries and conditional filtering

## Repository Contents

```text
.
├── spacex-launch-data-sql-analysis.ipynb
└── README.md
```

## Getting Started

Open the notebook with Jupyter and execute the cells in order:

```bash
jupyter notebook
```

The notebook uses SQL within the Jupyter environment. Check its data-loading cells for the expected SQLite database or source data.

## Scope

The project demonstrates exploratory SQL analysis rather than a production database service. Results depend on the specific dataset used.

## Related Projects

- [SpaceX Data Collection](https://github.com/Slimjoey56/SpaceX-Launch-Data-Collection-and-Wrangling)
- [SpaceX EDA](https://github.com/Slimjoey56/spacex_launch_data_eda)

## Author

Jehosaphat Brobbey Impiani  
[GitHub](https://github.com/Slimjoey56)