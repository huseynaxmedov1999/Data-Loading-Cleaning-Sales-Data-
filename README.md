## Project Overview

This project demonstrates a complete data cleaning and exploratory data analysis (EDA) workflow using Python and Jupyter Notebook.
The objective is to ensure data quality by handling missing values, correcting data types, and generating insights through basic visualizations.

## Project Structure

Data Cleaning(Sales Data).ipynb — Jupyter Notebook containing the full data cleaning and analysis process
sales_data_sample.csv — Raw dataset used for analysis
cleaned_data.csv — Final cleaned dataset
README.md — Project documentation

## Key Steps

Loaded the dataset from sales_data_sample.csv
Performed initial data inspection (shape, data types, missing values, duplicates)
Converted ORDERDATE to datetime format
Handled missing values by imputing "Unknown" where appropriate
Conducted exploratory data analysis (EDA), including:
Sales distribution
Order count by year
Top countries by number of orders
Exported the cleaned dataset to cleaned_data.csv
