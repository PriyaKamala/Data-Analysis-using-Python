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
