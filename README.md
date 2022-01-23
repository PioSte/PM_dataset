# Intro
I'm doing this project in order to get some practical experience with Pandas and time series data modeling. Hence, the work is ongoing, the processing is chaotic and the approach might not be the best.

And the dataset is…
# PM2.5 Data of Five Chinese Cities Data Set
[Data](https://archive.ics.uci.edu/ml/datasets/PM2.5+Data+of+Five+Chinese+Cities)

**Data Set Information:**

The time period is between Jan 1st, 2010 to Dec 31st, 2015. Missing data are denoted as NA.  

**Attribute Information:**

No: row number  
year: year of data in this row  
month: month of data in this row  
day: day of data in this row  
hour: hour of data in this row  
season: season of data in this row  
PM: PM2.5 concentration (ug/m^3)  
DEWP: Dew Point (Celsius Degree)  
TEMP: Temperature (Celsius Degree)  
HUMI: Humidity (%)  
PRES: Pressure (hPa)  
cbwd: Combined wind direction  
Iws: Cumulated wind speed (m/s)  
precipitation: hourly precipitation (mm)  
Iprec: Cumulated precipitation (mm)

# The goal
PM prediction based on weather (forecast).

# What to do with missing data?
Currently imputed with the scikit-learn `IterativeImputer`.