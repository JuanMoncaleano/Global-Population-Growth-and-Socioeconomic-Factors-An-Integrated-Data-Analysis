# Project 1

This repository explores the influence of socioeconomic factors on population growth at a global scale. It includes datasets related to population growth, safety, poverty, and education. The analysis involves data cleaning, integration, and visualization to gain insights into the relationship between these factors and population growth.

## Modules

The following Python modules are required for this project:

pandas
requests
json
matplotlib.pyplot
math
scipy.stats
numpy
plotly.express
 
A file called api_keys.py is required with a variable called geoapify_key that is assigned as your key from GeoApify.com. This file needs to be in the main repo as well as a copy inside the 'Cleaned_Datasets' folder.

## Summary

The repository features global datasets on topics including population growth, safety, poverty, and education. It contains Jupyter Notebooks which are used to clean and structure each of these initial four datasets. After processing, the cleaned data is saved as a CSV file, ready to be merged with others.

The data cleaning process utilizes API calls to GeoApify, which allows the standardization of syntax for successful merging and mapping.

The main analysis code can be found in the 'base_code_visualization' notebook. This code extracts data from each of the cleaned datasets, integrates them, and then generates visualizations to compare different socioeconomic factors with the growth rate over various years (depending on each dataset's unique time range).

These visualizations incorporate hypothesis testing calculations such as the correlation coefficient and p-value comparison.

## Data sources

Below you will find the links to the data sources used in this project:

The main reference data for countries can be found at Stefan Gabos's GitHub repository: [World Countries Data](https://github.com/stefangabos/world_countries/blob/master/data/countries/_combined/countries.csv)

For choropleth maps creation, Plotly's Python Library was used: [Choropleth Maps](https://plotly.com/python/choropleth-maps/)

The methodology to calculate growth rate was derived from this Indeed's guide: [How to Calculate Growth Rate](https://ca.indeed.com/career-advice/career-development/how-to-calculate-growth-rate)

The base data set for world population was taken from Kaggle: [World Population Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/world-population-dataset)

The data related to education was sourced from BarroLee's Dataset: [BarroLee Dataset](https://barrolee.github.io/BarroLeeDataSet/BLv3.html)

The poverty-related data was sourced from OWID's GitHub repository: [Poverty Data](https://github.com/owid/poverty-data/blob/main/datasets/pip_codebook.csv)

Safety-related data was taken from Vision of Humanity's Global Peace Index Maps: [Vision of Humanity Maps](https://www.visionofhumanity.org/maps/#/)

Built-in colorscales from Plotly's Python Library were used for visualization: [Built-in Colorscales](https://plotly.com/python/builtin-colorscales/)https://plotly.com/python/builtin-colorscales/

## Citations

HERE
