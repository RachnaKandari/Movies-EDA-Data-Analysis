# Movies EDA - Exploratory Data Analysis

Exploratory data analysis on a movie dataset, looking at how budget, gross earnings, ratings, and other attributes relate to each other.

## Problem Statement

No single model is built here; the goal is to understand the data itself: which movie attributes (budget, score, studio, release year) are associated with higher gross earnings, and where the data has quality issues (outliers, missing values) that would need to be addressed before any predictive modeling.


## Project Scope
Data cleaning and checks for missing values, duplicates, and data types.
Outlier detection on gross earnings using box plots.
Correlation analysis across numeric and categorical features, using Pearson, Kendall, and Spearman methods plus heatmaps.
Regression plots examining the relationship between budget and gross earnings, and between score and gross earnings.
Groupby analysis of top companies and years by gross revenue.

## Tools Used

pandas, numpy, matplotlib, seaborn

## Key Insights
Box plots show meaningful outliers in gross earnings, worth flagging before any further modeling.
Budget and gross earnings, and score and gross earnings, both show visible positive relationships in the regression plots.
A handful of production companies account for a disproportionate share of total gross revenue across years.

## Author

Rachna Kandari
kandari.rachna74@gmail.com | https://www.linkedin.com/in/rachna-kandari/
