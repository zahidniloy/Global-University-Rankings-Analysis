# Global-University-Rankings-Analysis

## Project Overview
This project explores and analyzes the global university rankings dataset obtained from the Center for World University Rankings (CWUR). The analysis includes profiling, cleaning, and modeling the dataset using statistical and machine learning techniques. The project concludes with a Tableau-based visualization story that summarizes key findings. The goal is to identify trends, regional patterns, and performance indicators that influence global university standings over time.

## Objective
1. Clean and profile the dataset to prepare it for analysis.

2. Explore statistical relationships between ranking metrics.

3. Perform geospatial visualization to analyze regional performance.

4. Apply supervised and unsupervised machine learning techniques to uncover trends and segment universities.

5. Create a data-driven story using Tableau to present final findings.

## Data Source
The dataset was retrieved from Kaggle:
World University Rankings – Kaggle Source
Filename: cwurData.csv

## Tools Used
Python (Jupyter Notebook)

Pandas, NumPy – Data Cleaning & Exploration

Seaborn, Matplotlib – Visualization

GeoPandas, Plotly – Geospatial Analysis

Scikit-learn – Machine Learning

Tableau – Final Visual Storytelling

## Data Cleaning
Filled missing values using column-wise mean imputation

Removed duplicate rows

Standardized country names by trimming whitespace

Verified year ranges and ensured consistent data types

Detected and clipped outliers in the score column

Saved the cleaned dataset to a separate CSV file for further processing

## Exploratory Data Analysis
Identified distribution of university scores and other ranking metrics

Explored year-over-year trends for top-ranked universities

Analyzed relationships between metrics like publications, influence, and alumni employment

Examined longitudinal performance of consistent top performers

## Geospatial Visualizations
Used choropleth maps to show distribution of top-performing universities by country

Highlighted countries with consistent performance across years

Compared performance of universities within and across regions

## Machine Learning – Regression
Built a supervised regression model to predict a university's score based on ranking metrics

Evaluated model using R-squared and mean squared error

Interpreted coefficients to understand feature importance

## Machine Learning – Clustering
Performed unsupervised learning using K-Means clustering

Grouped universities based on performance metrics into clusters

Interpreted clusters to uncover common characteristics among institutions

## Tableau Story
The final project is summarized in a Tableau Storyboard that walks through global university performance, top countries, consistent trends, and key metrics.

View it here:

Global University Rankings Tableau Story

https://public.tableau.com/app/profile/jacob.smith2124/viz/GlobalUniversityRankingsAnalysis20122015/GlobalUniversityAnalysis_Story
