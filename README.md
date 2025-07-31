# World Happiness Clustering Analysis

K-means clustering of 164 countries using World Happiness Report data (2005-2017). Groups nations by happiness factors to identify similar development patterns and policy insights.

## Dataset
- **Source:** World Happiness Report 2018
- **Coverage:** 164 countries, 2005-2017
- **Features:** GDP per capita, social support, life expectancy, freedom, generosity, corruption perceptions

## Analysis
- Aggregated multi-year data to country averages
- Used elbow method and silhouette analysis for optimal cluster selection
- Applied PCA visualization for cluster interpretation
- Identified meaningful country groupings for policy applications

## Files
- `happiness_clustering.ipynb` - Main analysis notebook
- `happiness_clustering.pdf` - PDF export of results  
- `WHR2018Chapter2OnlineData.csv` - Dataset

## Tech Stack
Python, scikit-learn, pandas, matplotlib, seaborn
