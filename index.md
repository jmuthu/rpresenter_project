Forecasting World Average Food Basket Prices 
========================================================
author: Joe Muthu
date: 14 Feb 2016
transition: fade
Introduction
========================================================

Food basket prices have been increasing steadily over the period of years. 

A Shiny application is created to forecast food prices based on the data gathered since 1976 from different world cities
by [UBS prices and earnings](https://www.ubs.com/microsites/prices-earnings/open-data.html). 


UBS Prices and Earnings Data
========================================================
Based on the data provided by UBS, average food prices were computed out of 32 cities from 1976 to 2015 as a time series data.

<img src="index-figure/unnamed-chunk-1-1.png" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" style="display: block; margin: auto;" />

Prediction Modeling 
========================================================
Used a linear model to forecast the outcome prices using the year as the predictor. 

<img src="index-figure/unnamed-chunk-2-1.png" title="plot of chunk unnamed-chunk-2" alt="plot of chunk unnamed-chunk-2" style="display: block; margin: auto;" />

Mean squared error rate for the model is 927. 

Application on Shiny Server
========================================================
Application is hosted [here](https://jmuthu.shinyapps.io/shiny_project/)
- Forecasts the price based on the given year and also plots the results. 
- Provides necessary documentation and links for reference and further analysis.


