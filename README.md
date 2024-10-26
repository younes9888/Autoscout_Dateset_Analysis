# Autoscout_Dateset_Analysis
Python,SQL,Power BI to analyse Autoscout dataset

## Project Overview

This project involves an analysis of the AutoScout24 used car sales data from 2019. 
We processed and analyzed this dataset to uncover insights into pricing, influential features, and patterns among used cars.

## Data Source
The dataset used for this analysis is a CSV file titled "AutoScout24_Car_Sales2019," available on [Kaggle](https://www.kaggle.com/datasets/duygujones/autoscout24-car-sales2019).


## Tools and Technologies
The following tools were employed to handle data cleaning, analysis, and visualization:

    Python: Data cleaning and initial exploration.
    MySQL: SQL queries for in-depth data analysis.
    PowerBI: Interactive reporting and data visualization.

## Data Cleaning and Preparation

In the initial data preparation phase, Python was utilized for:

    Data loading and inspection.
    Handling missing values.
    Data cleaning and formatting.

## Exploratory Data Analysis (EDA)

During the exploratory phase, we addressed key questions aimed at understanding the dataset's characteristics, such as:

    What is the price distribution of used cars in the dataset (mean, median, and distribution)?
    Which factors significantly influence the price of a used car (e.g., age, mileage, horsepower, brand)?
    Are there notable price variations based on brand or model?

## Data Analysis Using SQL

#### The following questions were answered using SQL queries:

    -Count the total number of cars in the database.
    -Identify the car with the highest price.
    -Calculate the average price of cars per brand.
    -List the top 10 cars with the highest mileage (km).
    -Count the number of cars using Diesel fuel.
    -Display all cars older than 5 years with less than 50,000 km.
    -Show the distribution of transmission types.
    -Display the price distribution based on brand and body type.
    -Compare the average horsepower (hp) of Diesel cars to those running on gasoline.
    -List cars with a power-to-weight ratio (hp_kw/weight_kg) greater than 0.1.
    -Display the newest cars per brand with prices below the brand's average.
    -Show cars with less than 100,000 km and more than three previous owners.
