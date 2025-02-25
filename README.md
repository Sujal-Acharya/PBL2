 AIR QUALITY PREDICTION PROJECT
 
 PROJECT OVERVIEW
This project aims to predict the Air Quality Index (AQI) and health impact score using key pollutant concentrations, including:

-CO (Carbon Monoxide)                                                                                 
-NO₂ (Nitrogen Dioxide)                                                                          
-SO₂ (Sulfur Dioxide)                                                                              
-Ozone                                                                              
-PM₁₀ (Particulate Matter ≤ 10µm)                                                                
-PM₂.₅ (Particulate Matter ≤ 2.5µm)                                                               
The AQI is calculated based on these six pollutant levels using a standard formula. The objective is to develop a predictive model that accurately estimates AQI values.

DATASET DESCRIPTION
The dataset consists of the following columns:

From Date – Start date of data collection                                                             
To Date – End date of data collection                                                     
CO, Ozone, NO₂, SO₂, PM₁₀, PM₂.₅ – Pollutant concentration values                                         
State – Location’s state                                                                         
City – Location’s city                                                        

This project will utilize machine learning techniques to analyze pollutant levels and predict AQI, helping in air quality assessment and environmental monitoring.

Tried to use XGBoost algorithm because it works well on structured data and handles missing values.
But for our main model, CNN-LSTM is used as LSTM is great for Time Series forecasting as AQI fluctuates seasonally and CNN extracts patterns and improve feature learning
