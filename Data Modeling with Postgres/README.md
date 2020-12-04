Purpose of the database:

The purpose of this database is to allow the analytics team at Sparkify to analyze the data they've been collecting on songs and user activity on their new music streaming app.Using this database, data professionals at Sparkify can perform apply Data Analysis and Data Science techniques on their song and log data to leverage data and make business decisions.

Database schema design and ETL pipeline

This database is built using Star Schema. It has the following Fact and Dimension tables.
Fact Table: songplays
Dimension Tables: Users, Songs, Artists, Time

To run the ELT pipeline, follow the below steps.
1.Run the sql_queries.py and create_tables.py python scripts. create_tables.py script creates tables based on the queries listed in sql_queries.py file.
2.Run the etl.py python script which inserts data into the tables.
3.Run the test.ipynb notebook to check if data is successfully inserted into the table.

Note: The data_view.ipynb file is used to take a first look at the data.