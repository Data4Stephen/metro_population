# metro_population
This Python script presents a UI that allows you to retrieve Metropolitan Statistical Area (MSA) population data from the US Census API, store it in an AWS Postgres database, and read / visualize the data.  This is intended to help learn the basics of Python, API requests, and interaction with cloud hosted databases.

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
