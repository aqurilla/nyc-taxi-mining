# NYC Taxi and Limousine Commission Dataset Mining

## Overview

  

In this project we analyze a subset of the NYC Taxi and Limousine Commission dataset (available [here](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page)). Specifically, we consider Green Taxi data from September 2015. Green taxis do not operate in the Hail Exclusionary Zone in Manhattan, south of West 110th St and East 96th St.

  

The main outcomes for this analysis were:

1. Obtained and cleaned the data

2. Performed exploratory data analysis to understand relevant trip metrics
- Modeled the trip distance distribution as log-normal
- Analyzed fare variations in trips originating from and terminating at NYC airports

3. Built a predictive model for the tip amount as a percentage of the total fare
- Performed feature engineering for including other possible relevant metrics while building the model
- Developed a Random Forest predictive model for the tip amount as a percentage of total fare, obtaining an R<sup>2</sup> = 0.89

## Instructions

Using a virtual environment for installing dependencies is recommended
```
$ conda create --name ds python=2
```
The rest of the dependencies can be installed in the virtual env using the following command-
```
$ pip install pandas jupyter numpy matplotlib seaborn scipy geopy scikit-learn  
```
The comprehensive list of all package requirements is specified in the `stable-req.txt` file.

After installing the dependencies, run the jupyter notebook from the terminal using:
```
$ jupyter notebook
```
