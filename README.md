# Udacity-Data-Modeling-with-Apache-Cassandra
Udacity Data Engineering Project 2: Data Modeling with Apache Cassandra

This project is for a startup, Sparkify, that is looking to be able to better understand their user's interaction with the music they play.

<h2>Project Description</h2>
The project uses Apache Cassandra as a database in order to create tables and queries that answer the specific questions for Sparkify.

All queries results are printed out to the terminal window.

<h2>Project Structure</h2>
The project includes multiple files and folders.
- event_data: A folder that contains the JSON metadata files.
- etl.py: The main program that does the ETL on the data and runs all functions to create tables, insert data, and run the queries.
- sql_queries.py: This file contains the SQL queries that are run which are not dynamically built
- sql_queries_helpers.py: This file contains functions that are helpers and run the dynamic SQL queries.

<h2>To run the project</h2>
Using terminal, in the project's directory, use the command `python3 etl.py`
