# Project: Student Exam Data Cleaning and Analysis

## Overview
This project uses the Pandas library to clean, organize, and perform a basic analysis on student marks data from an Excel file. The script processes raw data, calculates total marks, sorts students, and separates them into different academic streams.

## What I Did
The script performs the following data cleaning and analysis operations:

**Feature Engineering**: Created a new "Total Marks" column by summing the values from multiple subject columns.

**Data Sorting**: Sorted the entire dataset in descending order based on the new "Total Marks" column to easily identify top performers.

**Data Partitioning**: Split the single dataset into two distinct dataframes: one for "Bio students" and one for "CS students," based on which subject marks were present.

**Column Refinement**: Dropped the irrelevant subject columns from each split dataframe (e.g., dropped CS marks from the Bio student dataframe).

**Data Consolidation**: Combined the two new dataframes into a single, final output file that is organized by student stream.

## How to Run
Ensure you have the pandas and openpyxl libraries installed (pip install pandas openpyxl).

Place the raw data file, DPS_BOYS_SSC_II_2025.xlsx, in the same directory as the script.

Run the Python script from your terminal.

## Technologies Used
Python 3.x

Pandas

Openpyxl

## Output
The cleaned and analyzed dataset is saved to a new Excel file named cleaned_students_marks.xlsx.