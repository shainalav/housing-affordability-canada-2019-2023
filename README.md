# Housing Affordability in Canada (2019–2023)

## Overview:
This project explores how housing affordability has changed across Canadian provinces between 2019 and 2023. Using median after-tax income data and average housing prices, it creates a clear picture of affordability trends, regional disparities, and the widening gap between income and real estate prices. K-means clustering is also used to uncover provincial groupings based on affordability.

## Data Sources: 
* Median After-Tax Income (2019–2023): Statistics Canada https://www150.statcan.gc.ca/n1/daily-quotidien/250501/t002b-eng.htm
* Monthly Real Estate Prices: Canadian Real Estate Association https://stats.crea.ca/en-CA/

## Highlights:
* Cleaned and pre-processed two large datasets for provincial-level analysis
* Engineered an affordability ratio feature
* Calculated year-over-year changes in both income and home prices
* Visualized affordability trends using line plots and heatmaps
* Applied K-means clustering to identify groups of provinces with similar affordability patterns
* Compared affordability ratios to the historical benchmark (median multiple = 3.0)

## Key Findings:
* By 2023, British Columbia’s housing price was 13× its median income, the highest in Canada.
* Ontario’s housing prices rose by 46.9%, while income only rose 5.4% from 2019–2023.
* No province met the commonly accepted affordability threshold (median multiple of 3.0).
* The analysis confirms a national erosion of housing affordability during the pandemic years.

## How to Use: 
Clone the repo and open the .ipynb file in Jupyter Notebook to explore the analysis.
* git clone https://github.com/shainalav/housing-affordability-canada-2019-2023.git 
