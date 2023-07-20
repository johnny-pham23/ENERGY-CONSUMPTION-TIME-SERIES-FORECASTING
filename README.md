# UC Riverside Capstone Project


# Predicting Electrical Energy Consumption by Time Series Forecasting
 
# Goals
- Utilize Seasonal Autoregressive Integrated Moving Average with eXogenous variables (SARIMAX) approach to forecast weekly and monthly energy consumption.  
- Create visualizations of the dataset to gibe insight to seasonal patterns of electrical consumption.
- Use autocorrelation functions (ACF) and partial correlation functions (PACF) followed by grid searching to find the best model.

# Overview
Utilizing hourly data of electrical loads from Duke Energy Ohio and Kentucky Corp. (DEO&K) and joining historical air temperature data from Cincinnati Northern Kentucky International Airport, future energy consumption can be modeled and predicted by time series forecasting. Time series forecasting is a data science technique that analyzes time series data using statistics and modeling to make predictions and inform strategic decisions (Lazzeri, 2021). This project will predict the amount of electricity DEO&K will use over the next year.   

# Area of Study
![Pie chart of species](images/TemporalAnalysis.png) 

# Data Structure

|                  x|                 y|  acq_date| frp| acq_time|County|
|-------------------|------------------|----------|----|---------|------|
|-123.79012382714633| 39.49769932079566|2014-04-16| 5.7|     2051| 06045|

## Temporal analysis
Example output of temporal analysis:  
![Pie chart of species](images/AreaofStudy.png)  
Credits: Johnathan Pham

## Spatial Analysis
Example output of spatial analysis:  
![Pie chart of species](images/spatial_analysis100klegendsmall.png)  
Credits: Vraj Patel
