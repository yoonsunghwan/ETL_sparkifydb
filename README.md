# ETL_sparkifydb
Postgres database with tables designed to optimize queries on song play analysis  

https://labrosa.ee.columbia.edu/millionsong/  
https://github.com/Interana/eventsim  

## Description  
Build a Postgres database with a star schema using Python. The ETL pipeline will transfer data from local directories into the Postgres database. The data from the local directories come from the 2 links above.  

### etl.py 
Extract Transform and Load files from a filepath into a postgres database called sparkifydb 

### create_tables.py
Creates a database called sparkifydb, drops any existing tables, and then creates new tables.

### sql_queries.py
Contains sql_queries to drop, insert, create tables in the sparkifydb  

### test.ipynb  
Contains queries to test the script.

-----

To create a sparkifydb, first run create_tables.py and then run etl.py
To test whether the ETL is successful run test.ipynb
