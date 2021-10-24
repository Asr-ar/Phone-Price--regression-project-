# Phone Price Regression

## Abstract
The goal of this project was to use linear regression models to predict the prices of mobile phones based on features and charactristics.

## Data
A collection of phones and their features were scraped from **91mobiles.com**. Features include brand and model names, launch date, screen size, storage and battery.
- 2658 rows x 108 columns (Original)
- 2473 rows x 41 columns (Cleaned)


## Design

*Extraction, Formatting & Type Conversion*

All of the data was scraped from the website as strings (Objects) and needs extraction, formatting, and type conversion.

*Normalization*

Scaling of training data between the range of 1 and 0.

*Cross-Validation*

Cross validation of 4 different linear models (Simple Linear, LASSO, Ridge, ElasticNet) with training and testing data.

## Tools

Software Platform
- Jupyter Notebook

Programming Language
- Python
 
Python Libraries:

- Statistics libraries:
  - Sklearn
  - Statsmodels
 
- Data manipulation libraries:
  - Pandas
  - Numpy
 
- Web Scraping libraries:
  - BeautifulSoup
  - Selenim
 
- Visualization libraries:
  - Matplotlib
  - Seaborn
 
- Storage libraries
  - Pickle

## Communication
Slides containing visualizations
