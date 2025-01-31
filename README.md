# PySpark Data Processing

***

#### Purpose

This project leverages PySpark to execute data processing tasks on a large dataset. It encompasses a Spark SQL query and a data transformation operation to enhance data analysis and insights.

***

#### Requirements

1. Utilize PySpark for data processing on a substantial dataset.  
2. Incorporate a Spark SQL query and a data transformation.

***

#### ETL

Extract (E): Retrieves a dataset in CSV format from a specified URL.  
Transform (T): Cleans, filters, and enriches the extracted data, preparing it for analysis.  
Load (L): Loads the transformed data into a SQLite Database table using Python's sqlite3 module.  
Query (Q): Writes and executes SQL queries on the SQLite database to analyze and extract insights from the data.

****

Dataset: [Baskin Robbins Ice-Cream](https://raw.githubusercontent.com/prasertcbs/basic-dataset/master/baskin_icecream.csv)

***

### Commands to Run the Repo

To run the project, you can use the Makefile and follow these commands:
1. ```
   # To install the required the python packages
   make install
   ```
2. ```
   # To check code style
   make lint
   ```
3. ```
   # To run tests
   make test
   ```
4. ```
   # To format the code
   make format
   ```
5. ```
   # To extract data
   make extract
   ```
6. ```
   # To tranform data
   make transform_load
   ```
7. ```
   # To query data
   make query
   ```
***

#### Successful Formatting, Linting and Testing

On running make format, make lint, and make test in actions, it executes succesfully.

![make lint format](https://github.com/nogibjj/afraa-n_Mini-Project-5/assets/143756865/3d2317bf-4aa3-43a5-9b2b-6944022fd48a)
![make test](https://github.com/nogibjj/afraa-n_Mini-Project-5/assets/143756865/7c2b932a-a38d-45d4-8bf6-acd0e312df61)

