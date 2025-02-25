# Spiritual Data Hub

This repository contains data analysis exploring potential correlations between lunar cycles and crime rates in Los Angeles.

## Project Overview

The project analyzes LAPD crime data from 2020 to 2024, focusing on:
- Daily crime patterns in relation to moon phases
- Statistical analysis of crime rates during different lunar cycles
- Visualization of crime distribution across moon phases

## Data Sources

- **LAPD Crime Data (2020-2024)**: Comprehensive crime statistics from [data.gov](https://catalog.data.gov/dataset/crime-data-from-2020-to-present)
- **Moon Phase Data**: Calculated using the `ephem` astronomical library

## Analysis Components

### 1. Moon Phase Categories
We analyze crime rates across eight distinct moon phases:
- New Moon
- Waxing Crescent
- First Quarter
- Waxing Gibbous
- Full Moon
- Waning Gibbous
- Last Quarter
- Waning Crescent

### 2. Key Visualizations
- Bar charts showing average daily crimes by moon phase
- Density plots of crime distribution
- Statistical comparisons between different moon phases

### 3. Statistical Analysis
- Calculation of average daily crime rates for each moon phase
- Comparison with overall average crime rates
- Analysis of crime patterns during rising and falling moon phases

## Technologies Used

- Python
- Pandas for data manipulation
- Matplotlib and Seaborn for visualization
- Ephem for astronomical calculations
- Scipy for statistical analysis

## Getting Started

1. Clone the repository
2. Install required dependencies: `pandas`, `matplotlib`, `seaborn`, `ephem`, `scipy`
3. Run the Jupyter notebook `crime_data_analysis.ipynb`

## Directory Structure

```
spiritual-data-hub/
├── data/
│   └── lapd-crime-2020-2024.csv
├── crime_data_analysis.ipynb
├── crime_data_analysis.py
└── README.md
```
