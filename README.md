# Road Accident Analysis Report for New York City from 2012-2024
This repository contains detailed data analysis on New York city road accidents from 2012 to 2024. Figuring out overall accident cases to time series analysis to get insights on the traffic situations, this repo helped an NGO to bring some unique solutions for the traffic system 


## Overview

This project aims to analyze and predict accident occurrences in a given area based on various factors such as location, time, contributing factors, and vehicle types. By leveraging machine learning models and time series analysis techniques, we can gain valuable insights into accident patterns, trends, and potential future occurrences. This README.md file provides an overview of the project structure, data sources, methodologies used, and instructions for running the code.


## Project Structure

The project is organized into the following directories:

- **data**: Contains the dataset files used for analysis and prediction.
- **notebooks**: Jupyter notebooks containing exploratory data analysis (EDA), model development, and visualization scripts.
- **scripts**: Python scripts for data preprocessing, model training, and evaluation.
- **images**: Images and plots generated during analysis and visualization.
- **models**: Saved machine learning models for future use.
- **reports**: Project reports, including documentation and presentations.

## Data Sources

The dataset used in this project consists of accident records collected over a certain period. The dataset includes various attributes such as crash date, crash time, location (latitude and longitude), borough, contributing factors, and vehicle types involved.

## Methodologies

The project employs the following methodologies:

1. **Predictive Modeling**: Utilizes machine learning algorithms such as Linear Regression, Random Forest, and XGBoost to predict the number of persons injured or killed in accidents based on the available features.

2. **Time Series Analysis**: Investigates the trend and seasonality in accident occurrences over time using techniques like decomposition, autocorrelation analysis, and Augmented Dickey-Fuller test.

3. **Trend Analysis**: Analyzes trends in the number of accidents over different time periods (e.g., years, months, days) to identify patterns and potential causes.

4. **Forecasting**: Uses ARIMA (AutoRegressive Integrated Moving Average) model for time series forecasting to predict future accident occurrences.

## Predictive Model Building

The predictive model building process involves the following steps:

1. Data preprocessing: Cleaning, transforming, and encoding categorical variables.
2. Feature selection: Identifying relevant features for model training.
3. Model training: Fitting machine learning algorithms on training data.
4. Model evaluation: Assessing model performance using metrics such as RMSE (Root Mean Squared Error).

## Time Series Analysis

Time series analysis explores the temporal patterns in accident occurrences using statistical techniques and visualizations.

## Trend Analysis

Trend analysis examines the long-term trends and periodicities in accident data to understand underlying patterns.

## Forecasting

Forecasting predicts future accident occurrences using time series forecasting models, enabling proactive measures for accident prevention and management.

## Dependencies

The project requires the following dependencies:

- Python (version X.X)
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- statsmodels

## Usage

To run the project:

1. Clone the repository to your local machine.
2. Install the required dependencies using pip or conda.
3. Navigate to the notebooks or scripts directory.
4. Run the Jupyter notebooks or Python scripts for analysis, modeling, and visualization.

## Contributing

Contributions to the project are welcome. Feel free to open issues for bug fixes, feature requests, or improvements.


###NB: Every 30 days later, I update the data, results and other overviews
