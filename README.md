# EDA_marathon_Project

This project explores the TWO_CENTURIES_OF_UM_RACES.csv dataset, available on Kaggle, which documents two centuries of ultramarathon race results. The analysis focuses on a subset of the data—50 km and 50 mi races in the US during the year 2020—and aims to extract insights through data cleaning, transformation, visualization, and exploratory analysis.

## Project Steps

### Import Libraries

Essential Python libraries for data analysis and visualization are imported, including pandas, numpy, matplotlib, seaborn, and plotly.

### Load the Dataset

The dataset is loaded and the structure is examined to understand the available information.

### 1. Pre-filtering the Data

We focus on a specific subset:

    Only 50 km or 50 mi races

    Only races held in the United States

    Only races that took place in the year 2020

### 2. Cleanup and Transformation

    Age Calculation: Derived from birth year and race year

    Time Conversion: Race time strings are converted into float hours

    Drop Unnecessary Columns: Removal of redundant or irrelevant data fields

### 3. Standardization and Renaming

Column names are standardized to improve readability and usability in further analysis.

### 4. Visual Data Exploration

Initial exploration using histograms, scatter plots, and other visual tools to understand distributions and correlations.

### 5. Speed vs Age Analysis

Analyzing how average speed changes across different ages.

### 6. Boxplot: Age × Gender

Comparing performance distributions by gender across different age groups.

### 7. Business Insights and Questions

Addressing practical questions, such as:

    Is there a significant speed difference between men and women?

    Which age groups perform best in 50mi races (with a minimum of 20 participants)?

### 8. Speed by Season

Investigating if race season (spring, summer, fall, winter) influences athlete performance.

### 9. Interactive Dashboard with Plotly

An interactive dashboard is developed using Plotly to explore metrics dynamically.
