# Blue-Book-for-Bulldozers - Regression with Time Series Analysis

## Overview

This Jupyter notebook addresses the Blue Book for Bulldozers challenge, a regression problem involving time series data analysis. The objective is to predict the auction sale price of bulldozers based on various features. The notebook covers data preprocessing, model building, and evaluation using regression techniques.

1. **Train.csv:** is the training set, which contains data through the end of 2011.
2. **Valid.csv:** is the validation set, which contains data from January 1, 2012 - April 30, 2012.
3. **Test.csv:** contains data from May 1, 2012 - November 2012.

## Steps

1. **Problem Definition:**
   - Predict the auction sale price of bulldozers using regression models and time series analysis.

2. **Data:**
   - The dataset is sourced from Kaggle's "Blue Book for Bulldozers" competition (https://www.kaggle.com/c/bluebook-for-bulldozers). It includes features such as machine configuration, usage, and historical usage patterns.

3. **Evaluation:**
   - The primary metric for evaluation is the RMSLE (Root Mean Squared Log Error) between the actual and predicted auction prices. The goal is to minimize this metric.

4. **Features:**
   - Key features include machine configuration details, usage metrics, and historical information, enabling a comprehensive analysis for predicting auction prices.

5. **Time Series Analysis:**
   - Due to the temporal nature of the data, time series analysis techniques are employed, considering the impact of time on the auction prices of bulldozers.

## Usage

1. **Notebook Link:**
   - View the notebook using [nbviewer](https://nbviewer.org/github/AnkitNub/Bluebook-for-bulldozer/blob/main/Bluebook-for-bulldozers.ipynb).

2. **Execution:**
   - Open the Jupyter notebook locally:

     ```bash
     jupyter notebook Bluebook-for-bulldozers.ipynb
     ```

   - Run through each cell to get optimal results.

3. **Outcome:**
   - Analyze the results, model performance, and insights derived from the regression analysis.

