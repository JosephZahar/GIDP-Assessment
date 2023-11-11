<img alt="R" src="https://img.shields.io/badge/R%20-blue.svg?style=flat&logo=R&logoColor=white" /> <img alt="RStudio" src="https://img.shields.io/badge/RStudio-75AADB?logo=RStudio&logoColor=white&style=flat" /> <img alt="git" src="https://img.shields.io/badge/-Git-F05032?style=flat&logo=git&logoColor=white" /> 

# GIDP World Bank Project

## Table of Contents
1. [Overview](#overview)
2. [Contents](#contents)
3. [Data Sources](#data-sources)
4. [Requirements](#requirements)
5. [Usage](#usage)

## Overview

This website is designed for the assessment of R programming skills, focusing on statistical analysis and data visualization. It includes sections on basic stats, summary statistics, aggregate stats, outlier detection, poverty measures, Lorenz curves, and Gini coefficients. The notebook utilizes various R packages like `dplyr`, `readr`, `data.table`, `ggplot2`, and others.

## Contents

1. **Basic Stats**  
   Loading necessary R packages and the dataset for subsequent questions.

2. **Summary statistics of GDP per capita by region**  
   Calculation of weighted standard deviation, mean, min, max, and count of non-NA values of GDP per capita, grouped by region and date.

3. **Aggregate Stats**  
   Computation of aggregated statistics for life expectancy, GDP, and international poverty, along with data reshaping and visualization.

4. **Find outliers**  
   Identification of outlier columns in a data table for life expectancy, GDP, and Gini index.

5. **Simulated data**  
   Loading of a simulated dataset for the following sections.

6. **Poverty measures**  
   Calculation of poverty metrics using the Foster-Greer-Thorbecke (FGT) poverty measures.

7. **Lorenz curve**  
   Construction and visualization of Lorenz curves for income distribution.

8. **Gini coefficient**  
   Calculation of the Gini coefficient to measure income inequality.

## Data Sources

Data for this assessment is primarily sourced from:

- Public datasets hosted on [GitHub](https://github.com/randrescastaneda/pub_data/raw/)

## Requirements

- R version: 4.3.2
- Required packages: `readr`, `dplyr`, `waldo`, `data.table`, `spatstat`, `ggplot2`, `DT`

## Usage

Each section in the notebook is self-contained and can be run independently, provided the initial data loading steps are completed. Uncomment the `waldo::compare` lines for comparison with reference datasets.
