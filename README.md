# COVID19-Social-Factors
Regression analyses to examine social factors in COVID incidence rates.

This project explores how social factors (from the CDC’s Social Vulnerability Index) were associated with COVID19 incidence rates in U.S. states and counties during 2020. The analysis was conducted in R using regression models to identify which community characteristics were most strongly linked to COVID19 spread.

## Project Goal

The goal was to identify leading social factors related to COVID19 incidence at the state and county level.

## Data Sources

COVID19 case data (county and state level, 2020)

CDC Social Vulnerability Index (SVI) data

## Methods

Data cleaning and merging of COVID + SVI datasets

Exploratory data analysis

Correlation analysis

Multiple regression analysis


## Key Insights

Certain socioeconomic and demographic factors showed strong correlations with higher COVID19 incidence.

Regression analysis highlighted how income, minority status, and housing conditions contributed to disparities in case rates.

Modest R-squared values indicate that many other factors, such as public health policies and healthcare infrastructure, were not accounted for in this analysis. Future work could incorporate these variables and explore alternative modeling techniques to better capture the complex dynamics at play. Additionally, temporal analyses could reveal how these factors evolved over the course of the pandemic.

## Reproducibility

To reproduce the analysis, clone the repository and open notebooks/SocialFactors_COVID.Rmd in RStudio.

Download the original CDC SVI data from the official portal. Link available in 'data' folder.

Cleaned datasets (clean_states.csv, clean_counties.csv) are included for convenience.

Original raw datasets were provided as part of a course assignment. Equivalent public datasets are available from the CDC SVI and public COVID-19 trackers.
