# BigData
*Weather Forecast of Big Data on Linux*
This project utilizes Apache Spark to analyze weather data, aiming to forecast weather trends based on historical data. The analysis includes data preprocessing, exploratory data analysis, and linear regression modeling to understand the influence of various weather parameters on temperature.
**Prerequisites**
Before running this project, ensure you have the following installed:
Python 3.8 or newer
Apache Spark 3.x
Hadoop 2.x or newer (for HDFS operations)
**Data Description**
The data for this project is stored in HDFS and includes the following fields:
number_sta: Station number
lat: Latitude
lon: Longitude
height_sta: Elevation of the station
date: Observation date and time
dd: Wind direction (in degrees)
ff: Wind speed
precip: Precipitation
hu: Humidity
td: Dew point temperature
t: Temperature
psl: Sea level pressure
The dataset is read from HDFS using the path hdfs://localhost:9000/datasets/WeatherForcast.
Features Implemented
Data Cleaning: Handling missing values and casting data types.
Exploratory Data Analysis: Statistical summaries and visualizations of different weather parameters.
Linear Regression Model: A model to predict temperature based on other weather parameters.
**Additional Notes**
Modify the HDFS paths according to your environment setup.
The code includes detailed logging for debugging and tracking the computation stages.
