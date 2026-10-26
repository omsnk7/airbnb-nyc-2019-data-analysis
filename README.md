# airbnb-nyc-2019-data-analysis
Exploratory data analysis and data cleaning of NYC Airbnb listings using Python.
# Airbnb NYC 2019 — Exploratory Data Analysis

## Project Overview

This project explores Airbnb listings in New York City using Python. The goal is to understand listing prices across neighborhoods and room types, investigate the relationship between reviews and price, and analyze host listing distributions.

## Objectives

- Identify neighborhoods with the highest average listing prices.
- Compare average prices across room types.
- Investigate the relationship between review counts and listing prices.
- Examine how listings are distributed among hosts.

## Data Cleaning

- Converted `last_review` to datetime format.
- Filled missing `reviews_per_month` values with zero.
- Removed listings missing critical values.
- Identified and removed price outliers using the Interquartile Range (IQR) method.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Dataset

**Source:** [New York City Airbnb Open Data — Kaggle](https://www.kaggle.com/dgomonov/new-york-city-airbnb-open-data)

The dataset contains Airbnb listing information for New York City in 2019.

## Project File

`Airbnb_NYC_2019_Data_Analysis.ipynb` — contains the data cleaning process, exploratory analysis, visualizations, and results.

## Key Skills Demonstrated

Data cleaning, missing-value handling, outlier detection, descriptive statistics, exploratory data analysis, and data visualization.
