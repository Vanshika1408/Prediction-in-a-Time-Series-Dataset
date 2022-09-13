# Prediction-in-a-Time-Series-Dataset
Project 1- Building Innovative Systems (UCS757)


We've been given an excel file of road dataset with data regarding road section/pavement where length of a road is approximately 25kms and the full length of the road is divided into subsections. Number of sections are approximately 100. Some IoT based companies have deployed a few electronic sensors to get the values for predesignated 13 parameters. For each subsection of road, time series data has been given yearwise. We need to predict the parameters 9-13 for the year 10 for every road section. First the datatset needs to be preprocessed and unwanted columns should be removed and missing values needs to be filled with the mean, median, standard deviation etc. The dataset is splitted into training and testing data with respect to the year. So, all the entries from year 1-9 constitutes the training data and entries with year 10 constitutes the testing one. Different time series model with different parameters are being experimented with. For every column the model is being fit and RMSE is calculated. The ultimate goal is to make the RMSE (Root Mean Square Error) as low as possible. Different models being experimented are:

1. ARMA (Automatic Regressive Moving Average) Model
2. ARIMA (Automatic Regressive Integrated Moving Average) Model
3. SARIMAX (Season Auto Regressive Integrated Moving Average with eXogenous factors) Model


The best model is chosen finally and the average RMSE of the model in this case is 51.956349795352864.
