# Netflix Data Analysis

## Overview

This project analyzes Netflix content data using R to explore patterns and relationships within the platform's catalog. The analysis uses data manipulation, visualization, and statistical techniques to investigate several hypotheses about Netflix movies and TV shows.

The project was originally completed as part of a university course and is presented here as part of my data analysis portfolio.

## Tools and Technologies

- R
- Jupyter Notebook
- dplyr
- ggplot2
- tidyr
- stringr

## Dataset

This project uses the **Netflix Movies and TV Shows** dataset created by Shivam Bansal and available on Kaggle.

Dataset: https://www.kaggle.com/datasets/shivamb/netflix-shows

The dataset is provided under the **CC0: Public Domain** license.

The dataset file used in this project is stored in:

`data/netflix_titles.csv`

## Analysis

The project is organized around five hypotheses. Each hypothesis is explored by preparing and filtering the relevant data, creating visualizations, and interpreting the resulting patterns.

### Hypotheses

1. **The most common genres vary by the type of content (Movies vs. TV Shows).**
2. **The number of titles added to Netflix has changed over time.**
3. **The duration of movies differs by rating category.**
4. **The top countries producing content have shifted over the years.**
5. **TV shows with specific keywords in the description are more popular in certain genres.**

The analysis demonstrates techniques including:

- Data cleaning and transformation
- Filtering and grouping data
- Exploratory data analysis
- Data visualization with ggplot2
- Working with categorical and numerical variables
- Interpreting patterns and trends in real-world data

## Project File

The complete analysis, R code, visualizations, and explanations can be found in:

`a-netflix-data-analysis.ipynb`

GitHub can display Jupyter notebooks directly in the browser, so the analysis can be viewed without downloading or running the project.

## Running the Project

To run the notebook locally, you will need an environment that supports Jupyter notebooks with an R kernel, along with the required R packages:

```r
library(dplyr)
library(ggplot2)
library(tidyr)
library(stringr)
```

The notebook loads the dataset from the `data` folder, so the repository structure should be kept intact when running the analysis.

## Purpose

This project demonstrates my experience using R for data analysis, data visualization, and working with a real-world dataset.
