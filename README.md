# spacex-launch-data-sql-analysis
SQL-based exploratory data analysis of SpaceX launch records using SQLite and Jupyter Notebook. Includes data querying, aggregation, filtering, and mission performance insights.
# SpaceX Launch Data SQL Analysis

This project explores SpaceX launch data using SQL queries executed within a Jupyter Notebook environment.

The analysis focuses on extracting insights from historical launch records through SQLite and the `ipython-sql` extension.

## Project Overview

The notebook demonstrates practical SQL skills by analyzing SpaceX mission data, including:

- Identifying unique launch sites
- Calculating total and average payload masses
- Examining mission outcomes
- Investigating landing success rates
- Filtering launches by date, payload, and launch site
- Ranking landing outcomes over time

## Technologies Used

- Python
- Jupyter Notebook
- SQLite
- SQL
- ipython-sql
- Pandas

## Dataset

The dataset contains historical SpaceX launch information, including:

- Launch dates
- Booster versions
- Launch sites
- Payload masses
- Customers
- Mission outcomes
- Landing outcomes

## Key SQL Concepts Demonstrated

- `SELECT`
- `DISTINCT`
- `WHERE`
- `LIKE`
- `GROUP BY`
- `ORDER BY`
- `COUNT()`
- `SUM()`
- `AVG()`
- `MIN()`
- Subqueries
- Aggregate functions

## Project Structure

```text
├── jupyter-labs-eda-sql-coursera_sqllite.ipynb
├── Spacex.db
├── README.md
└── requirements.txt
