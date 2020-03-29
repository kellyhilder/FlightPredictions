01-LoadFiles.ipynb
 - reads in 36 files (3 years, by month 2017-2019)
 - combines each year into a single data frame and then exports a csv for each year

02-CleanFlights2017.ipynb
03-CleanFlights2018.ipynb
04-CleanFlights2019.ipynb
 - performs cleaning on each of the data frame for each year and exports a clean csv

05-Comparison.ipynb
 - compares to see which airlines exist in 2017, but not 2018 and vice versa

06-EDAFlights2017.ipynb
07-EDAFlights2018.ipynb
 - reads in the clean flight csv's and performs further EDA
 - also run basic logistic regression models for 2017 and 2018

08-Atlanta2017.ipynb
 - creates and cleans a data frame of just the Atlanta airport
 - adds in origin weather
 - performs a basic logistic regression model

09-Burbank2017.ipynb
10-Burbank2017.ipynb
 - creates and cleans a data frame of just the Burbank airport
 - runs a comparison of the airlines and destinations in 2017 and 2018
 - adds in origin and destination weather

11-BurbankInitialModelling.ipynb
 - reads in the 2017 and 2018 Burbank dataframes
 - runs a number of initial models (logistic regression, KNN, decision tree, random forest, MLP Classifier)

12-TimeSeries2017.ipynb
 - runs ARIMA and FacebookProphet models on the 2017 Burbank data

13-Burbank2019.ipynb
 - creates and cleans a data frame of just the Burbank airport
 - runs a comparison of the airlines and destinations in 2018 and 2019
 - adds in origin and destination weather

14-BurbankFinalModelling.ipynb
 - reads in the 2017, 2018 and 2019 Burbank csv files
 - performs feature engineering and hyperparameter optimization
 - run a final logistic regression model

15-PlotlyVisualizations.ipynb
 - uses plotly express to create visualizations for the Burbank data
