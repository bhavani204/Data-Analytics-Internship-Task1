# Data-Analytics-Internship-Task1
# Task 1 - Data Immersion & Wrangling

## Overview

This project was completed as part of the ApexPlanet Data Analytics Internship Task 1. The objective was to understand the dataset, identify data quality issues, perform data cleaning and transformation, and create an analysis-ready dataset.

## Dataset Information

The dataset contains sales transaction records with the following columns:

* Order ID
* Customer Name
* Product
* Sales
* Profit
* Order Date

## Data Dictionary

| Column Name   | Description                      |
| ------------- | -------------------------------- |
| Order ID      | Unique identifier for each order |
| Customer Name | Name of the customer             |
| Product       | Product purchased                |
| Sales         | Revenue generated from the order |
| Profit        | Profit earned from the order     |
| Order Date    | Date of purchase                 |

## Data Quality Assessment

The following issues were identified:

* Missing values
* Duplicate records
* Data type inconsistencies
* Potential outliers

## Data Cleaning Steps

1. Loaded the dataset into Google Colab using Pandas.
2. Identified missing values using `isnull()`.
3. Filled missing values using appropriate methods.
4. Detected and removed duplicate records.
5. Converted date columns into proper datetime format.
6. Performed exploratory checks for outliers.
7. Verified data consistency after cleaning.

## Tools Used

* Python
* Pandas
* NumPy
* Google Colab
* GitHub

## Files Included

* Original Dataset
* Cleaned Dataset
* Data Dictionary
* Jupyter/Colab Notebook
* README.md

## Results

* Successfully cleaned the dataset.
* Removed duplicate records.
* Handled missing values.
* Standardized data formats.
* Produced an analysis-ready dataset for further analysis.

## Conclusion

Task 1 provided hands-on experience in data cleaning and preprocessing, which are essential steps in any data analytics workflow. The cleaned dataset is ready for exploratory data analysis and business intelligence tasks.
