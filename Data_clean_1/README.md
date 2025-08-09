# Project: Raw Data Cleaning with Pandas

## Overview
This project uses Python's Pandas library to transform a raw CSV file into a clean, usable dataset. The script addresses common issues such as unnecessary columns, inconsistent text formatting, and missing or improperly typed values.

## What I Did
The script performs the following cleaning operations:

**Column Removal**: Removed irrelevant columns ("Peak" and "All Time Peak") to streamline the dataset.

**Text Cleaning**: Used regular expressions (regex) to clean string data in "Actual gross" and "Tour title" for consistency.

**Data Type Conversion**: Converted the "Ref." column into a numerical format by removing non-numeric characters, filling missing values with linear interpolation, and casting the final column to the integer type (Int64).

## How to Run
Install pandas (pip install pandas).

Place the raw data file (my_file (1).csv) in the same directory.

Run the Python script from your terminal.

## Technologies Used
Python 3.x

Pandas

## Output
The cleaned dataset is saved as cleaned_my_file (1).csv.
