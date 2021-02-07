# Real Estate Market Data Exploration in major French cities

![paris](https://media-cms.louvrehotels.com/static/styles/default/public/2020-01/paris-header-hotels-kyriad.jpg)

The objective of this project is to perform real estate data exploration of major French cities to understand very
well the real estate market in France.

The dataset used is a 5-years data history of real estate transactions in France (real_estate_transactions.csv).

The dataset contains details for each transaction: sale date, localization (city, postal code), type of residence, type of sale, land area, living area, number of
rooms, price, etc.).

The exploration of this dataset is done by using Spark, because the analysis should also be able to apply on very large datasets distributed on a Hadoop cluster, for instance to analyze the entire real estate market for all cities in France.

Challenges here are to explore all possible aspects of this real estate market (variables, relationships between variables, trends, patterns, outliers, etc.).

The notebook is divided into the following parts:
- Correlation between price and living area
- Correlation between number of rooms and living area
- Average price per year
- Average price/m² per year
- Number of properties per city
- Average price per city
- Number of properties per local type¶
- Average price per local type
- Average price of apartments per city
- Average price of houses per city
- Average price of dependencies per city
- Number of properties per sale type
- Average price per sale type
- Evolution of the average price per city per year
- Evolution of the number of properties per city per year
- Key findings and conclusions
