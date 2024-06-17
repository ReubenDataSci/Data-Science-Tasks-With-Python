# Pandas-Data-Science-Tasks
This is a set of real world data science tasks completed using the Python Pandas library.

## Overview
We use Python Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

## Setup 
To access all of the files I recommend you fork this repo and then clone it locally.

### Data Sources
Sales Data: The primary datasets used for this analysis is the "sales_data_csv" file, containing detailed information about eacg sales made by the company for the 12 months of the year 2019.

### Tools
- Python [Download here](https://www.python.org/downloads/release/python-3123/)
- Installing Jupyter Notebook: [Download here](https://jupyter.readthedocs.io/en/latest/install.html)
- Installing Pandas library:  [Download here](https://pandas.pydata.org/pandas-docs/stable/install.html) 
### Data Cleaning/Preparation
We start by cleaning our data. Tasks during this section include:

1. Drop NaN values from DataFrame
2. Removing rows based on a condition
3. Change the type of columns (to_numeric, to_datetime, astype)


## Exploratory Data Analysis (EDA)
Once we have cleaned up our data a bit, we move the data exploration section. In this section we explore 5 high level business questions related to our data:

1. What was the best month for sales? How much was earned that month?
2. What city sold the most product?
3. What time should we display advertisemens to maximize the likelihood of customer’s buying product?
4. What products are most often sold together?
5. What product sold the most? Why do you think it sold the most?

To answer these questions we walk through many different pandas & matplotlib methods. They include:

1. Concatenating multiple csvs together to create a new DataFrame (pd.concat)
2. Adding columns
3. Parsing cells as strings to make new columns (.str)
4. Using the .apply() method
5. Using groupby to perform aggregate analysis
6. Plotting bar charts and lines graphs to visualize our results
7. Labeling our graphs

 
