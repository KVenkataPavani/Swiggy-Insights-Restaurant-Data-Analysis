# Swiggy Insights: Restaurant Data Analysis

## Table of Contents

1. [Overview](#overview)
2. [Data Exploration](#data-exploration)
3. [Data Preprocessing](#data-preprocessing)
4. [Exploratory Data Analysis](#exploratory-data-analysis)
5. [Conclusion](#conclusion)
6. [Requirements](#requirements)
7. [How to Run](#how-to-run)
8. [License](#license)

## Overview

This project conducts an exploratory data analysis (EDA) on Swiggy's restaurant sales data. The focus is on uncovering trends related to restaurant ratings, cost distribution, and popular cuisines, with the aim of providing actionable insights for Swiggy and restaurant owners. The analysis leverages Python libraries like `pandas`, `numpy`, `matplotlib`, and `seaborn` for data manipulation and visualization.


## Data Exploration

The dataset used in this analysis contains information about various restaurants listed on Swiggy, with columns such as:
- `Restaurant`: Name of the restaurant
- `City`: City where the restaurant is located
- `Avg ratings`: Average rating given by customers
- `Price`: Average price of meals at the restaurant
- `Food type`: Comma-separated list of cuisines offered by the restaurant

### Basic Information:
The dataset is loaded from a CSV file which gathered from kaggle[https://www.kaggle.com/datasets/abhijitdahatonde/swiggy-restuarant-dataset], and basic statistics such as shape, column types, and the first few rows are displayed. Missing values and duplicate rows are handled accordingly.

## Data Preprocessing

Data preprocessing steps:
- **Missing values**: Identified and handled, including filling or removing missing values.
- **Duplicates**: Removed to ensure the accuracy of the analysis.
- **Data type conversions**: Converted relevant columns (e.g., `Price`) to numeric formats for analysis.
- **Rating categorization**: Categorized restaurants into different rating ranges based on `Avg ratings`.

## Exploratory Data Analysis

The analysis uncovers the following insights:

### Restaurant Distribution
- Number of unique cities served by Swiggy.
- Total number of restaurants and unique restaurant names.
- The most popular food chains based on frequency.

### Customer Reviews
- Distribution of average ratings for restaurants.
- Pie chart showing the percentage of restaurants in different rating categories.

### City Performance
- Cities with the highest number of restaurants.
- Cities with the highest average ratings.
- The city with the best food (highest average rating).

### Cost Analysis
- Distribution of restaurant prices.
- Top 10 most expensive restaurants.

### Cuisine Popularity
- Most common cuisines based on the `Food type` column.
- Most popular cuisines among highly-rated restaurants (`Avg ratings > 3.5`).

## Conclusion

The analysis provides actionable insights into restaurant ratings, price distribution, popular cuisines, and city performance. These insights can help Swiggy and restaurant owners make more informed decisions to optimize restaurant offerings and improve customer satisfaction.

## Requirements

To run this project, the following libraries are required:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

You can install these dependencies using `pip`:

```bash
pip install pandas numpy matplotlib seaborn
