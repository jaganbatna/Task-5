# Titanic Survival Exploratory Data Analysis (EDA)

This project explores the Titanic passenger dataset to identify the key factors that influenced survival during the disaster. The analysis focuses on statistical and visual examination using Python, Pandas, Matplotlib, and Seaborn.

## Project Structure

- `titanic.csv`  
  Dataset used for analysis

- `Titanic EDA.ipynb`  
  Jupyter Notebook containing the full exploratory analysis

- `Exploratory Data Analysis Report.pdf`  
  PDF report summarizing findings and visuals

## Problem Statement

The core question driving this project:

Which passenger characteristics were most strongly associated with surviving the Titanic sinking?

The analysis investigates demographic and travel-related features such as sex, passenger class, age, fare, and family size to explain survival patterns.

## Objectives

- Understand the dataset structure and quality
- Explore distributions and relationships between features
- Identify factors linked to survival outcomes
- Present insights supported by visuals and statistics

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key Steps Performed

- Data loading and inspection (`.info()`, `.describe()`)
- Missing value analysis
- Univariate and bivariate visualizations
- Survival comparison across:
  - Sex
  - Passenger class
  - Fare levels
  - Embarkation port
- Correlation analysis with heatmap

## Main Insights

- Female passengers had a much higher survival rate
- 1st class passengers survived more often than 2nd and 3rd class
- Higher fares were associated with higher survival probability
- Family-related features had limited impact
- Cabin data was mostly missing and not useful

## Results

The analysis shows that survival was strongly influenced by:

- Gender
- Social class
- Ticket price

These patterns reflect social and structural conditions during the event.

## How to Run

1. Clone the repository
2. Install dependencies
3. Open the Jupyter Notebook
4. Run all cells

