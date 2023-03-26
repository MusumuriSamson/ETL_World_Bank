## Extract Transform Load (ETL) process for the World Bank Data

### Table of Contents 

1. [Installation](#installation)
2. [Objective](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

You must install pycountry, chardet on your local machine.

Install the library using `pip`:

```
pip install pycountry
```
```
pip install chardet
```

## Objective<a name="motivation"></a>

This project demonstrates a comprehensive approach of ETL process which is an 
essential phase in data management and analysis process. Data is extracted from World Bank Data, transformed into a useable format, and loaded into a target system. The aim is to make the data clear, accurate, comprehensive, and consistent. Data reading, data cleaning, data mapping, and data integration are all carried out in the process. 

## File Descriptions <a name="files"></a>

There is a single notebook file `ETL.ipynb` that showcases the entire process . 

The data folder contains the following files 

Input Files 

1) `population_data.csv` - Consists statistical data related to Population, Employment, Health, GDP, Energy Consumption, etc. for all the countries in a csv format
2) `population_data.json` - Consists statistical data related to Population, Employment, Health, GDP, Energy Consumption, etc. for all the countries in a json format
3) `rural_population_percent.csv` - A data set containing the rural population
4) `projects_data.csv` - A dataset containing the projects initiated in all the countries
5) `mystery.csv` - A mystery dataset for which the utf code is unknown
6) `gdp_data.csv`- A dataset containing GDP values for all countries across the years

Output Files

1) `countrydata.json` - Exported data in json format
2) `countrydata.csv`- Exported data in csv format
3) `worldbank.db`- Exported data in database format



## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Data is taken directly from [World Bank](https://data.worldbank.org)

The data is made available under the Open Database License (ODbL): https://opendatacommons.org/licenses/odbl/summary/. Any rights in individual contents of the database are licensed under the Database Contents License: http://opendatacommons.org/licenses/dbcl/1.0/
