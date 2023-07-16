# metro_population
This Python script presents a UI that allows you to retrieve Metropolitan Statistical Area (MSA) population data from the US Census API, store it in an AWS Postgres database, and read / visualize the data.  There are also separate commands for dropping all records from the population as well as inserting the Census population dataframe into the database.  This is intended to help me learn the basics of Python, API requests, and interaction with cloud hosted databases.

# User Interface
<img width="480" alt="Screenshot 2023-07-16 at 12 18 47 PM" src="https://github.com/Data4Stephen/metro_population/assets/139660501/27b1e5a8-714f-4266-9873-41877cdcb572">


# Database Schema
* METROPOLITAN_POPULATION
  * MSA_CODE
  * YEAR
  * POPULATION
* MSA_CODES
  * MSA_TITLE
  * MSA_CODE
  * note: table loaded with MSA 5-digit codes and names from following source: https://www2.census.gov/programs-surveys/cps/methodology/2015%20Geography%20Cover.pdf 

# To-Do
* Add user input validations (particularly for Census API parameters)
* Error Handling
* Implement better custom SQL query editor
