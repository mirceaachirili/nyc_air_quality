# [Air Quality Analysis in New York City](https://github.com/mirceaachirili/nyc_air_quality/blob/main/analysis.ipynb)

This project conducts a comprehensive analysis of air quality trends in New York City, focusing on various pollutants and their geographical distribution across the five boroughs and different neighborhoods.

# Dataset

The dataset used in this project contains air pollutant measurements from multiple locations in New York City, spanning several years. Each observation in the dataset represents a measurement of a specific air quality indicator in a specific location and year.

[Dataset link](https://data.cityofnewyork.us/api/views/c3uy-2p5r/rows.csv?accessType=DOWNLOAD)

# Analysis

The analysis performed in this project includes:

- An exploration of overall air quality trends in NYC, including changes in the levels of specific pollutants over time.
- A comparison of air quality indicators across different boroughs and neighborhoods.
- An investigation into whether certain pollutants are more prevalent in specific areas or during certain time periods.
- The development of predictive models using machine learning techniques to forecast future air quality levels based on past data.

# Results

Key findings from the analysis include:

- The levels of various pollutants have generally decreased over the years, suggesting that air quality in NYC has been improving.
- Differences exist across boroughs, with some showing higher levels of certain pollutants than others.
- Fine Particulate Matter (PM2.5) shows strong correlations with several other pollutants.
- Our XGBoost model, which used past pollutant levels as predictors, was able to predict PM2.5 levels with a reasonable degree of accuracy.

# Future Work

Future extensions of this work could include more sophisticated modeling approaches, the incorporation of additional predictors such as weather or traffic data, or a deeper analysis of the health impacts of air pollution.
