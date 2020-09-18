# Timeseries Data Analysis Snippets 
## For timestamped earth science data

### 1. DateTimeFormatInDepth - Part 1.ipynb

Imported the data of flood occurances of at Boulder, Colorado, USA from earthpy dataset. The data represents the precipitation and weather data of that area from 2003-2013. Later this notebook explores various options of `pandas.parse_csv()` function `na_values`, `index_col`, `parse_dates` and later it presents some functions from matplotlib to display scatter plot. Then resampled the data on their `datetime` indices and plotted them. Atlast, I tried to subset the data in a particular date range and used **matplotlib.DateFormatter** to format the date labels on x-axis of the plot. 

### 2. DateTimeFormatInDepth - Part 2.ipynb

Imported the data of Temperature and Precipitation in July 2018 for Boulder, Colorado. Firstly imported the dataset without considering the date column as `datetime` object. Later, I used the `parse_csv()` from pandas to import the dataset with options `na_values`,`index_col`,`parse_dates` to correctly import the data indexed on `date` column of the dataframe. After that, I attempted one scatter plot and one bar plot using the dataframe. 
