# Python, Pandas & SQL Server --- Order Data Analysis

A hands-on ETL and data analysis project demonstrating how to work with
a dataset in Python, load data into a relational database, and analyze
order data using SQL.

The project combines **Python, Pandas, Microsoft SQL Server, SQLAlchemy,
PyODBC, and T-SQL** in a practical workflow covering data preparation,
database loading, and analysis.

## Project Overview

This project demonstrates an end-to-end data workflow using Python, Pandas, and Microsoft SQL Server to prepare, load, and analyze order data.

The project covers:
- **Data Preparation:** Inspecting and preparing tabular data using Pandas.
- **Database Integration:** Loading prepared data into SQL Server using SQLAlchemy and PyODBC.
- **SQL Analysis:** Querying order data using T-SQL to derive insights.

## Architecture and Workflow

1. **Dataset:** Obtain the order dataset from the original or an authorized source.
2. **Data Processing:** Load and inspect the dataset using Python and Pandas.
3. **Data Preparation:** Clean and prepare the data for database loading.
4. **Database Connectivity:** Connect Python to SQL Server using SQLAlchemy and PyODBC.
5. **Data Loading:** Load the prepared data into Microsoft SQL Server.
6. **SQL Analysis:** Run T-SQL queries to analyze order data and derive insights.
## Technology Stack

 | Technology | Purpose |
|---|---|
| Python | Data handling and workflow orchestration |
| Pandas | Loading, inspecting, and preparing tabular data |
| Jupyter Notebook | Interactive development and execution |
| Microsoft SQL Server | Relational data storage |
| SQLAlchemy | Python database integration |
| PyODBC | Connectivity between Python and SQL Server |
| T-SQL | Querying and analyzing order data |

## Repository Contents

  ---------------------------------------------------------------------------
 | File | Description |
|---|---|
| `Kaggle_to_Pandas_to_SQLServer.ipynb` | Notebook for dataset inspection, preparation, and SQL Server integration |
| `df_orders_analysis.sql` | SQL queries for order data analysis |
| `README.md` | Project overview, workflow, and setup instructions |
  ---------------------------------------------------------------------------

## Prerequisites

-   Python
-   Jupyter Notebook or JupyterLab
-   Pandas, SQLAlchemy, and PyODBC
-   Microsoft SQL Server
-   A compatible Microsoft ODBC Driver for SQL Server
-   The dataset used by the notebook, obtained from its original or
    authorized source

## Setup and Execution

1.  **Obtain the dataset.** Download the dataset used by the notebook
    from its original or authorized source.
2.  **Prepare Python.** Install the required packages, including Pandas,
    SQLAlchemy, and PyODBC.
3.  **Configure SQL Server.** Ensure that a SQL Server instance and
    target database are available.
4.  **Review connection settings.** Open
    `Kaggle_to_Pandas_to_SQLServer.ipynb` and update file paths,
    server/database details, and authentication settings for your
    environment.
5.  **Run the notebook.** Execute the cells in order to inspect and
    prepare the data and perform the database-loading steps.
6.  **Run the SQL analysis.** Open `df_orders_analysis.sql` in SQL
    Server Management Studio (SSMS) or another compatible SQL client,
    select the correct database, and execute the queries.

## What This Project Demonstrates

-   Working with tabular data using Python and Pandas
-   Preparing data for relational database loading
-   Connecting Python applications to SQL Server
-   Using SQLAlchemy and PyODBC for database connectivity
-   Writing T-SQL queries to analyze order data
-   Combining Python-based data preparation with SQL-based analysis
