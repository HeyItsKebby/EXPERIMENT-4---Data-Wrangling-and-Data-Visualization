# EXPERIMENT-4---Data-Wrangling-and-Data-Visualization

Python script/code for the given problems: ECE BOARD EXAM PROBLEM
## Prerequisites

Before attempting the problems, make sure you are familiar with the following concepts:

- **Importing Libraries**: Essential for accessing functionalities provided by external libraries (`pandas`, `matplotlib`, `seaborn`).
- **Data Input and Output**: Reading data into DataFrames using methods like `pd.read_excel()` and displaying data.
- **Indexing and Selection**: Accessing specific data points using integer-based (`iloc`) and label-based (`loc`) methods.
- **Boolean Indexing and Conditional Selection**: Filtering data based on conditions (e.g., `df[df['column'] > value]`).
- **Column Subsetting**: Selecting specific columns from the DataFrame (e.g., `df[['col1', 'col2']]`).
- **Logical Operations**: Combining multiple conditions to filter data (e.g., `(df['col1'] > value1) & (df['col2'] < value2)`).

## Introduction

This repository contains a Python script (in a Jupyter Notebook) designed to analyze the ECE Board Exam 2 dataset. The goal is to perform data wrangling and data visualization to present various insights from the dataset.

## Dataset

Download the board2.xlsx file to get the dataset.

## Instructions

1. **Download and Setup:**
   - Download the board2.xlsx file to get the dataset.
   - Place the dataset in the same directory as your Jupyter Notebook or specify the path in your script.

2. **Data Wrangling and Visualization:**
   - **Data Frames:**
     Create the following data frames based on the dataset:
     - **Instru**: Data frame with columns `[“Name”, “GEAS”, “Electronics >70”]` where `Track` is constant as `Instrumentation` and `Hometown` is `Luzon`.
     - **Mindy**: Data frame with columns `[“Name”, “Track”, “Electronics”, “Average >=55”]` where `Hometown` is constant as `Mindanao` and `Gender` is `Female`.

   - **Visualization:**
     Create a visualization that illustrates how different features contribute to the average grade. Analyze whether the chosen track in college, gender, or hometown has a significant effect on the average score.

3. **Submission:**
   - **Notebook Submission:**
     Implement your solution in a Jupyter Notebook.
   - **Upload:**
     Submit the completed Jupyter Notebook to the designated submission bin.


## Example

Here is an example of how the `Vis` data frame should be formatted:
```plaintext
Name    Gender  Track          Math
S4      Male    Instrumentation 65
S11     Female  Communication    48
S22     Female  Communication    64
