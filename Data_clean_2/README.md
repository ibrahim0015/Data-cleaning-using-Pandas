# Project: Order Data Cleaning and Standardization with Pandas

## Overview
This project uses Python's Pandas library to clean and standardize an Orders.csv dataset. The script addresses common issues like duplicate entries, missing values, and inconsistent text casing to prepare the data for analysis.

## What I Did
The script performs the following cleaning operations:

**Duplicate Removal**: Identifies and removes duplicate rows to ensure data uniqueness.

**Missing Data Handling**: Drops rows with a missing "Order Date," a critical field for a sales dataset.

**Text Standardization**: Formats city and name columns with proper capitalization and converts the "Email" column to lowercase.

**Value Imputation**: Replaces NaN values in the "Discount" column with 0, ensuring consistent data types for calculations.

## How to Run & Output
First, install the pandas library (pip install pandas).

Next, place the raw Orders.csv file in the same directory as the script.

Finally, run the script from your terminal. The cleaned data will be saved as Cleaned_Orders.csv.

## Technologies Used
Python 3.x

Pandas