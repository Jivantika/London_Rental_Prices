# London_Rental_Prices
Exploring and predicting London's rental prices based on webscraped Zoopla data

## Authors: 
Maxwell S., Maya S., Alejandro A., Nikolay P., Clara G.

## Project description:
Based on Zoopla data and LSOA (Lower Layer Super Output Areas) data from the London Statistics Office, the following analysis aims to generate deeper insights on London's rental prices and to build a prediction model of rental prices for a given property, based on its features (e.g. number of beds) and neighborhood characteristics (e.g. public transport accessibility).

The data underlying our analysis stems from two sources. Firstly, we web-scraped [data on rental listings in central London](https://www.zoopla.co.uk/to-rent/map/property/london/?new_homes=include&include_retirement_homes=true&include_shared_ownership=true&include_shared_accommodation=true&price_frequency=per_month&q=London&results_sort=newest_listings&search_source=home&pn=1) from Zoopla, London’s leading aggregator of real estate data, using Python’s Beautiful-Soup library (Zoopla 2021). Secondly, we drew [data on neighborhood characteristics by LSOA (Lower Layer Super Output Areas)](https://data.london.gov.uk/dataset/super-output-area-population-lsoa-msoa-london) from the London Statistics Office and mapped these areas to postcodes (London Statistics Office 2014).

## Included files: 
Data.zip: Raw and cleaned data<br>
London_Rental_Prices_Notebook.ipynb: Notebook including code of analysis<br>