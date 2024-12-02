Title: Median Earnings Between the Sexes (Men and Women) Data

## Introduction

This dataset provides quarterly statistics on employment and earnings in the United States from 2009 to 2010. It includes data for both men and women, expressed in current and constant dollars. A line plot is created to show the trend of number of workers (men vs women) in its repective year. A bar plot is created using geom_bar() to show the current median weekly earnings, with each gender represented by a different fill color (blue for men and pink for women).

Explanations of Columns (input):

Year and Quarter: Indicate the time period of the data.
Number of workers (in thousands): Total, men, and women workers.
Median weekly earnings (in current dollars): Median earnings broken down by gender.
Median weekly earnings (in constant dollars): Adjusted for inflation, showing earnings in constant purchasing power.
Uses:

Using this data we can:
* Analyze workforce trends by gender and time.
* Study the gender pay gap and its inflation-adjusted changes.
* Examine economic trends during the late-2000s recession.

## Organization of Project

Project Directory Structure
src:Contains all scripts. Includes functions and data cleaning scripts.

doc:Stores all documentation files (e.g., README, manuals, or guides).

data:Holds raw data files used in the project.

results:Includes all output files produced by the scripts, such as visualizations, tables, or processed datasets.


## How to Run Files

#1 Data Loading and Cleaning:
Import and clean the dataset, and rename dataset to data.csv.

#2 Data Analysis:

Visualize the key trends in the data using ggplot2 (for example, visualization 1).

Data Transformation:

Create derived metrics, such as percentage differences between men's and women's earnings.
Aggregate data by year or other categories for macro-level analysis.
Visualization:

Develop insightful plots to convey trends, such as:
Line charts showing workforce growth or decline.
Bar charts highlighting earnings gaps.
Inflation-adjusted comparisons of current vs. constant dollar earnings.
Modeling and Insights:

Outputs:
Visualizations (results folder):

Plots generated:
* Line graph: Number of workers (men vs. women) over time.
* Bar chart: Median weekly earnings comparison by gender.

Cleaned data frames:
workers_long: Reshaped data for the number of workers (long format).
meoww: Reshaped earnings data for visualizations.


## Documentation:

Include comments and clear explanations in the code for reproducibility.
Provide an overview of methods used and insights gained in a markdown report or presentation.
Output:

Save clean data and visualizations in the designated results directory (/Users/julianguyen/Desktop/CSPC/Earnings_Sex/Results).
3. Goal
This project is designed to:

Deliver a clear understanding of workforce and earnings trends during 2009-2010.
Highlight gender disparities in employment and pay.
Use a modular, clean coding approach to ensure the project is extensible and reusable.


