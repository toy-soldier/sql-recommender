# SQL Recommender

A a SQL-driven ranking system that scores Philippine stocks using basic fundamentals like profitability, valuation, and leverage.

## Goal

Build a pure-SQL engine that computes financial ratios, compares companies to industry benchmarks, and outputs Buy/Hold/Sell recommendations.

## Structure

- /data : CSVs (companies, financials, industry_benchmarks)
- /sql  : SQL scripts (cleaning, ratios, ranking, recommendations)
- /notebooks : Notebook to narrate SQL queries and results
- /output : final CSVs

## Environment file

This project uses the environment file `.env` in the home directory to store database credentials.  The file contents are as follows:

    DB_SERVER=localhost
    DB_PORT=<database port; usually 5432>
    DB_NAME=fundamentals
    DB_USER=<database username>
    DB_PASSWORD=<database password>

## Tools

1. SQL
2. Jupyter Notebook
3. Python
