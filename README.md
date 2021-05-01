# ETL_Project

Proposal: Thomas and I are young, aspiring Data Scientists fresh off the new hire line at Nasa. Day one we have a project coming straight from the top. The Director of NASA wants us to comb through the Confirmed Exoplanet dataset and the Kepler Objects of interest database to analyze the exoplanets that fall in both datasets and the common parameters they share.

## Finding Data

Two sources of data utilized for this project

https://data.world/nasa/exoplanets

https://www.kaggle.com/nasa/kepler-exoplanet-search-results


## Data Cleanup & Analysis

Transformation - irrelevant columns dropped, renamed, and identified as Primary or Foreign Keys for SQL (relational database). 

## Project Report

Extract - 

Two sources of data utilized for this project. These datasets where formatted in CSV files. 

https://data.world/nasa/exoplanets

https://www.kaggle.com/nasa/kepler-exoplanet-search-results

Transform - 

The data needed to be cleaned up to something useful. Columns renamed, dropped non useful columns/ NaN values. 

Purpose would be to join the datasets and query overlapping exoplanet data to identify common characteristics of the exoplanets. 

One could then run aggregate queries to find information about the exoplanets that are found in both datasets. 

Load - 

Both datasets where loaded into SQL. SQL was chosen because these data sets are final, related, and structured. Ease of use and relational functions. 

