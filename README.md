# Project-1-Crime-Demographics-and-City-Response

**Submitted By:** Dong Yi Kim | Elizabeth Salas martinez | Saif Gorges | Saloni Gupta | Sooyeon Kim </br>
_Date_: november, 12th, 2020\
ETL - **Crime-Demographics-and-City-Response** <br/>

![Toronto image](./Project-1---Crime-Demographics-and-City-Response/Resources/.png)


## Introduction
It might be a challenge to choose where to live in Toronto when you decide to move or open a business. In this project, we built a database that demonstrated the crime rate, income range, house prices, and population of the neighbourhoods. We wanted to find this information about each neighbourhood and if there are correlations between those measures. We also wanted to look at if those kinds of measures affect the Starbucks locations so that we know what real business consider most when they choose the locations. Our main assumptions were that maybe there is a negative correlation between income/house prices and crime rates, and the average income of neighbourhoods will affect the Starbucks locations. We will also be looking at how the city responds to crime rates in Toronto.

## Data Extraction
In this project we extracted, transformed, and loaded different types of datasets as Income, Crime, Rental House Prices, Red Light Camers, Speeding Count and Starbucks locations.

- Our main sources:
 - Toronto Neighbourhood Data - Toronto City Open Data
 - Toronto Neighbourhood Income - Toronto City Open Data
 - Toronto Crime Data - Toronto City Open Data
 - Toronto House Price - Toronto City Open Data
 - Red Light Cameras - Kaggle
 - Speeding Count - ArcGIS API
 - Starbucks Locations - Kaggle

- We make an API call on

## Data Engineering

![Data_Engineering_image](./Project-1---Crime-Demographics-and-City-Response/Resources/Data_Engineering.png)

## Data Transformation
- We used a Pandas functions in Jupyter Notebook to transform all CSV files, scraped data, and API request responses.
- We reviewed the files and transformed into a dataframes.
- We used a python transformation functions for data cleaning, joining, filtering, and aggregating.
- Several columns removed
- Duplicate rows was removed, and successfully managed.
- We conducted some aggregation to find totals for comparison in the datasets.

## Load

- Income Table
- Crime Table
- Starbucks Table
- Red Light Cameras Table
- Speeding Table
- House Rental Prices Table

## Analysis

Questions answered:-
- Which areas in Toronto have high average income/crime rates?
- Are there more red light cameras in lower income regions?
- How does crime rate vary for neighborhoods in different  Income Range?
- Is there a higher crime rate in lower income regions?
- Is there a correlation between house prices and crime rates?
- Are there more Starbucks locations in higher income neighborhoods?


