# Capstonepj-DE0223 (Part 1)
# COVID-19 Data Analysis

This repository contains code to retrieve and analyze COVID-19 data from a Microsoft Access database using SQL queries and Python.

## Prerequisites

- Python 3.x
- Required libraries: pyodbc, pandas

## Getting Started

1. Clone the repository.
2. Install the required libraries: pyodbc, pandas.
3. Update the connection string in the Python code.
4. Run the code using the command: `python main.py`.

## SQL Queries

The code executes SQL queries on the COVID-19 data stored in the Access database:

1. Retrieve the total confirmed, death, and recovered cases.
2. Retrieve the total confirmed, deaths, and recovered cases for the first quarter of each year.
3. Retrieve a summary of all the records.
4. Retrieve the percentage increase in the number of death cases from 2019 to 2020.
5. Retrieve information for the top 5 countries with the highest confirmed cases.
6. Compute the total number of drop or increase in confirmed cases from month to month.

## Output

The code generates pandas DataFrames with the query results for further analysis or visualization.


