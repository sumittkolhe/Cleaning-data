# Data Cleaning Project

This repository contains a Jupyter notebook that demonstrates comprehensive data cleaning techniques applied to two different datasets: NYC Airbnb listings and YouTube trending videos from multiple countries.

## Project Overview

The primary goal of this project is to showcase essential data cleaning techniques including:

- Handling missing values
- Removing duplicates
- Standardizing data formats
- Detecting and handling outliers
- Enriching data with additional context
- Creating derived metrics for analysis

## Datasets

### Dataset 1: NYC Airbnb Listings
- Source file: `dataset1/AB_NYC_2019.csv`
- Contains information about Airbnb listings in New York City including location, price, availability, and reviews

### Dataset 2: YouTube Trending Videos
- Multiple country data files in `dataset2/` directory:
  - `USvideos.csv` - United States trending videos
  - `GBvideos.csv` - United Kingdom trending videos
  - `CAvideos.csv` - Canada trending videos
  - And more country-specific files
- JSON category mapping files for each country (e.g., `US_category_id.json`)
- Contains information about trending videos including views, likes, comments, and metadata

## Notebook Contents

The `Data_Cleaning_Project.ipynb` notebook is organized into three main sections:

1. **NYC Airbnb Data Cleaning**
   - Loading and exploring the dataset
   - Handling missing values in name, host_name, and reviews
   - Removing duplicate listings
   - Standardizing text fields and categories
   - Detecting and handling price outliers
   - Analyzing cleaned data with visualizations

2. **YouTube Video Data Cleaning**
   - Loading and exploring the US dataset
   - Adding category names from JSON mapping
   - Handling missing values and duplicates
   - Calculating engagement metrics
   - Handling outliers in views, likes, etc.
   - Analyzing tags and categories

3. **Multi-Country YouTube Analysis**
   - Loading data from multiple countries
   - Comparing metrics across countries
   - Analyzing category popularity differences
   - Examining common tags across regions

## Key Techniques Demonstrated

- Data integrity verification
- Missing data identification and resolution
- Duplicate record detection and handling
- Data standardization and normalization
- Statistical outlier detection using IQR method
- Feature engineering to create derived metrics
- Data visualization for cleaned data

## Getting Started

To run this notebook:
1. Ensure you have Jupyter Notebook or JupyterLab installed
2. Install required libraries: pandas, numpy, matplotlib, seaborn
3. Open `Data_Cleaning_Project.ipynb` in Jupyter
4. Run all cells or step through cells sequentially

## Results

After cleaning, both datasets are ready for advanced analysis with:
- No missing values in critical fields
- Standardized formats for text and categorical data
- Outliers identified and handled
- Enriched with additional context and derived metrics
- Cross-country comparisons for the YouTube dataset

This project demonstrates practical data cleaning techniques essential for any data analysis or machine learning project. 