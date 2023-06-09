## Sales-Data-Analytics and Insights Project
This repository contains a Python project for analyzing sales data and deriving valuable insights. The project utilizes various Python libraries and techniques to process, analyze, and visualize sales data, enabling users to gain meaningful insights and make data-driven decisions.

## Introduction

Sales data analytics plays a crucial role in understanding business performance, identifying trends, and making informed decisions. This project aims to provide a comprehensive solution for analyzing sales data using Python. By leveraging the power of Python libraries such as Pandas, NumPy, and Matplotlib, this project enables users to:

- Import and preprocess sales data.
- Perform data cleaning and data quality checks.
- Explore data using descriptive statistics and visualizations.
- Analyze sales trends, patterns, and correlations.
- Generate insightful reports and visualizations.

## Features
- Importing and loading sales data from various file formats (e.g., CSV, Excel).
- Data cleaning and preprocessing to ensure data quality.
- Descriptive statistics and summary metrics for sales data analysis.
- Visualizations including bar plots, line graphs, and scatter plots.
- Sales trend analysis and forecasting.
- Correlation analysis between sales and other factors.

## Background-Information:
I have used Python libraries like Pandas & Python Matplotlib to analyze and answer business questions about 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc.

We start by cleaning our data. Tasks during this section include:

- Drop NaN values from DataFrame
- Removing rows based on a condition
- Change the type of columns (to_numeric, to_datetime, astype)
Once I have cleaned up thr data a bit, I performed the data exploration section. In this section I have tried to answered 4 high level business questions related to our data:

- What was the best month for sales? How much was earned that month?
- What city sold the most product?
- What time should we display advertisemens to maximize the likelihood of customer’s buying product?
- What product sold the most? Why do you think it sold the most?

To answer these questions we walk through many different pandas & matplotlib methods. They include:

- Concatenating multiple csvs together to create a new DataFrame (pd.concat)
- Adding columns
- Parsing cells as strings to make new columns (.str)
- Using the .apply() method
- Using groupby to perform aggregate analysis
- Plotting bar charts and lines graphs to visualize our results
- Labeling our graphs
