In this Project we are going to work with COVID19 dataset, published by John Hopkins University, 
which consist of the data related to cumulative number of confirmed cases, per day, in each Country.
Also we have another dataset consist of various life factors, scored by the people living in each country around the globe.  
We are going to merge these two datasets to see if there is any relationship between the spread of the the virus in a country and how happy people are, living in that country.

First weneed to import all the required packages like:
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt


After having cleaned the datasets by removing all the unnecessary columns we go ahead with performing below tasks:
1:Aggregating Data by Country using [grouby()]
2:Calculating a Good Measure based on the data for ex for this data dataset we calculated the Maximum Infection Rate for each country
3:Create a new dataframe with only the expected columns
4:Perform cleaning and all required steps on the Worldhappiness Report
5:Setting the index to Country so that the two dataframes can be joined using country
6:Performing join between the two dataframes
7:Calculating a correlation Matrix which indicates the Correlation Coefficient between the various fields
8:Visualizing the results of our Analysis using Seaborn and Matplotlib packages.

Please refer the 'Covid 19 Data Analysis Notebook' for detailed explanation and visualizations.

One Aspect of the Analysis is that the visualization indicates that more developed countries show a greater rate of infection to Covid 19 as compared to less developed countries.This could be due to below factors:
1:Lack of sufficient number of Covid testing kits in the poorly developed countries due to which the the actual number of 
infected cases were not recorded.
2:It could also be due the fact that in the highly developed countries we have more people travelling in and out on a regular basis or maybe an already infected person may have landed in a country and that could have led to the spread of the infection.
