## Movie Correlation Project
## Overview
This project analyzes the relationship between movie budgets and gross earnings using Python. The objective is to understand how different features, such as budget, gross earnings, and others, correlate with each other. This analysis helps in identifying patterns and trends in movie data, which can be valuable for making informed decisions in the film industry.

## Project Structure
1.Data Preparation

*    Loading Data: The dataset is read from a CSV file containing movie information.
*    Handling Missing Data: Missing values in the budget and gross columns are handled by converting them to numeric values and filling missing entries with zeros.
*    Data Type Conversion: The budget and gross columns are converted to integers for accurate analysis.
*    Year Extraction: A new column, year_correct, is created to extract and format the release year of movies.

2.Data Cleaning

*    Sorting: The dataset is sorted based on gross earnings in descending order.
*    Removing Duplicates: Duplicate entries are removed from the dataset.

3.Data Visualization

*    Scatter Plot: A scatter plot is generated to visualize the relationship between movie budgets and gross earnings.
*    Regression Plot: Seaborn is used to create a regression plot with a fitted line to further explore the relationship between budget and gross earnings.

4.Correlation Analysis

*    Correlation Matrix: A heatmap is generated to show the correlation matrix for numeric features in the dataset.
*    Categorical Conversion: Categorical features are converted to numerical codes for correlation analysis.
*    Updated Correlation Matrix: The correlation matrix is updated to include the newly converted numerical features.
*    Correlation Pairs: Correlation pairs are extracted and sorted to identify high correlations.

## Key Findings

1.High Correlation: Votes and budget have the highest correlation with gross earnings.
2.Low Correlation: The company feature has low correlation with gross earnings.

## Requirements
Python 3.x
Pandas
NumPy
Matplotlib
Seaborn

You can install the necessary libraries using pip:

*     pip install pandas numpy matplotlib seaborn

Clone the repository:

*     git clone https://github.com/kaurn6538/Movie-Correlation-Pyton-Project.git

Navigate to the project directory:


*     cd movie-correlation-project
Ensure you have the required libraries installed and run the script to perform the analysis:

*     python movie_correlation_analysis.py

