# Seoul Bikeshare

This project utilizes the data gathered by the Rental bike service in Seoul about the demand of their bike rental for a period of 1 year from 1 Dec 2017 to 30 Nov 2018. The dataset contains various weather information for each day and the number of bikes rented. The dataset was downloaded from the [https://archive.ics.uci.edu/dataset/560/seoul+bike+sharing+demand](UC Irvine Machine Learning Repository.)

In this project, I do some data cleaning, analysis, and visualize bikeshare data. Then I try some traditional machine learning tools (Regression and Classification) on the dataset. This repository provides the jupyter notebooks for all the steps I took, along with notes, plots and results on the notebook itself which can be used as a report, enabling data-driven decisions and urban mobility research.

## Features

- **Data Import and Cleaning:** Load and preprocess raw bikeshare datasets.
- **Exploratory Data Analysis:** Discover trends, patterns, and insights in the bike rental.
- **Visualization:** Generate charts and maps to visualize bikeshare activity.
- **Predictive Modeling:** Build models to forecast demand, and try to identify the season based on other features.


## Files
- **seoul_bikeshare_regression.ipynb** This file begins with the initial cleaning of the data and some EDA. Then it moves to trying the different regression models from scikit-learn package to try to predict the demand for the bikes based on the other features. I then try to improve the models with some hyperparameter tuning and checking feature importance.

- **seoul_bikeshare_classification.ipynb** This file begins with the initial cleaning of the data. Then it moves to trying to predict the season based on the different weather information and the demand for the bike with the information for the date removed. I use different classification models from scikit-learn package to try to classifiy the season. I then try to improve the models with some hyperparameter tuning and using combination of different models.
