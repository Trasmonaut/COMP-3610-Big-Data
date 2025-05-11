# COMP-3601-Big-Data - Predictive Analysis of Weather in Trinidad and Tobago

## Group Members: 
    Jordhan Couteau (816036449)
    Lillian Charles    (816037199)
    Caleb Ramdath  (816038072)

## Overview

A predictive weather model for Trinidad and Tobago using historical weather data and XGBoost. Historical weather data was fed in on 16 reigions of Trinidad and Tobago into an XGBOOST model to predict what the future weather given a date and reigon might be in Trinidad and Tobago, based off what is was historically.This proejct allows persons to have a refrence of what the weather in future might be, down to specific features/aspects for a given date. This would facilitate better planning of daily activies further in the future. 

This data is used to train the model to predict the following for the different regions of Trinidad and Tobago:
* Max Actual Temp C
* Min Actual Temp C
* Average Actual Temp C
* Max Relative Temp C
* Min Relative Temp C
* Average Relative Temp C
* Dew Point C
* Humidity %
* WindSpeed MPH
* Cloud Cover %
* Visibiltiy Miles
* Precipiation mm

This was done for the following regions
* San Juan-Laventille
* Point Fortin
* Penal-Debe
* Digeo Martin
* Crown Point (Tobago)
* Talparo-Couva-Tabaquite
* Chaguanas
* Arima
* Piaco-Tunapuna
* Siparia
* Scarbrough (Tobago)
* Sangre Grande
* San Fernado
* Rio Claro-Mayaro
* Princes Town
* Port of Spain

Data Source - Visual Crossing's Historical Weather data for Trinidad and Tobago

##XGBoost and Weather Prediction

This app uses XGBoost to make it's predictions, through Chained Multiouput Regression, where the output from one model is used to influence the output of the one that follows it. The result is a model with an average of 98.47% accuracy, on Time Series data for Trinidad and Tobago.

##Weather Prediction app - TTPredict

These models were used to form the back end of a website, where users can input a date and location in Trinidad and Tobago, and be output with a prediction of the weather on that given date.
