# ETF Analyzer
Financial database and web application using SQL, Python, and the Voilà library to analyze the performance of a hypothetical fintech ETF.

# Analyze a Single Asset in the ETF
SQL SELECT statement is used with an f-string that reads all the PYPL data from the database. Using the SQL SELECT statement, the query will read the PYPL data from the database into a Pandas DataFrame.
The head and tail functions review the first five and the last five rows of the DataFrame.
Using hvPlot, an interactive visualization for the PYPL daily returns is created.
Using hvPlot, an interactive visualization for the PYPL cumulative returns is created.

# Optimize Data Access with Advanced SQL Queries
The closing prices for PYPL that are greater than 200 are completed through the following steps:
Write a SQL SELECT statement to select the dates where the PYPL closing price was higher than 200.0.
Using the SQL statement, read the data from the database into a Pandas DataFrame, and then review the resulting DataFrame.
Select the “time” and “close” columns for those dates where the closing price was higher than 200.0.
Find the top 10 daily returns for PYPL by completing the following steps:
Write a SQL statement to find the top 10 PYPL daily returns. Make sure to do the following:
Use SELECT to select only the “time” and “daily_returns” columns.
Use ORDER to sort the results in descending order by the “daily_returns” column.
Use LIMIT to limit the results to the top 10 daily return values.
Using the SQL statement, read the data from the database into a Pandas DataFrame, and then review the resulting DataFrame.

# Analyze the ETF Portfolio
Write a SQL query to join each table in the portfolio into a single DataFrame. To do so, complete the following steps:
Use a SQL inner join to join each table on the “time” column. Access the “time” column in the GDOT table via the GDOT.time syntax. Access the “time” columns from the other tables via similar syntax.
Using the SQL query, read the data from the database into a Pandas DataFrame. Review the resulting DataFrame.
Create a DataFrame that averages the “daily_returns” columns for all four assets. Review the resulting DataFrame.

# Technologies
import numpy as np

import pandas as pd

import hvplot.pandas

import sqlalchemy

# Use the Voilà library to deploy your notebook as a web application
<img src="Module Challenge 7/Viola Screenshots/Screen Shot 2022-05-08 at 8.04.40 PM.png">
<img src="Module Challenge 7/Viola Screenshots/Screen Shot 2022-05-08 at 8.05.26 PM.png">
