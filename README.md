# Student Performance EDA Readme

## Overview
This repository contains an Exploratory Data Analysis (EDA) on a student performance dataset. The analysis aims to explore and understand the patterns and relationships within the data, providing insights into factors influencing students' academic performance.

## Dataset
The dataset, stored in 'performance.csv,' consists of information on students' gender, race/ethnicity, parental level of education, lunch type, test preparation course completion, and scores in math, reading, and writing. The dataset contains 1000 entries with no missing values.

### Data Preparation
- Loaded the dataset using Pandas.
- Checked for missing values (None found).
- Explored data types: 3 numerical columns and 5 categorical columns.

### Descriptive Statistics
- Utilized `data.describe()` to generate summary statistics for numerical columns.

## Feature Engineering
- Calculated the average score for each student based on math, reading, and writing scores.
- Added a new column, 'average_score,' to the dataset.
- Saved the updated dataset as 'updatedperformance.csv.'

## Correlation Analysis
- Investigated the correlation between math, reading, and writing scores using a heatmap.
- Observed a strong positive linear correlation between the three scores.

## Exploratory Data Visualization
### Parental Education vs. Average Score
- Explored the relationship between parental education levels and average scores using a boxplot.
- Noted that students with parents holding a master's degree tend to have slightly higher average scores.

### Test Preparation vs. Average Score
- Examined the impact of completing a test preparation course on average scores using a boxplot.
- Identified that students who completed the test preparation course generally achieved higher scores.

### Gender vs. Average Score
- Investigated the connection between gender and average scores using a boxplot.
- Found that female students tend to have higher average scores.

## Distribution Analysis
- Visualized the distribution of parental education levels and race/ethnicity using bar graphs.

## Feature Importance Analysis
- Conducted a feature importance test using a Random Forest Regressor.
- Identified that reading score, writing score, and math score are the most important features influencing the average score.
- Visualized feature importance using a horizontal bar chart.

## Conclusion and Insights
- Positive correlation between parental education and student performance.
- Students completing a test preparation course tend to achieve higher scores.
- Female students generally have higher average scores.
- Reading and writing scores are the most influential factors in determining average scores.

## Repository Contents
- **performance.csv**: Original dataset.
- **updatedperformance.csv**: Dataset after feature engineering.
- **eda_analysis.ipynb**: Jupyter Notebook containing the complete EDA code.
- **README.md**: This file providing an overview of the EDA process and findings.

Feel free to explore the Jupyter Notebook for a detailed walkthrough of the analysis. If you have any questions or suggestions, please feel free to reach out.

Happy exploring!
