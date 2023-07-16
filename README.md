# metro_population
This Python script presents a UI that allows you to retrieve Metropolitan Statistical Area (MSA) population data from the US Census API, store it in an AWS Postgres database, and read / visualize the data.  This is intended to help learn the basics of Python, API requests, and interaction with cloud hosted databases.

# User Interface
********************************************************
Metropolitan Statistical Area (MSA) Population Interface
********************************************************

Select one of the following numeric options:
  1 - Read database table
  2 - Drop all records
  3 - Retrieve data from Census API
  4 - insert into database table
  5 - open SQL Query Editor (SELECT statements only)
  6 - Visualizer   

type EXIT at any time to stop the program

# Database Schema
* METROPOLITAN_POPULATION
  * MSA_CODE
  * YEAR
  * POPULATION
* MSA_CODES
  * MSA_TITLE
  * MSA_CODE 
