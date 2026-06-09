# Citi Bike Ridership Analysis

## Project Overview

This project investigates a decline in Quarter 1 Citi Bike ridership between 2025 and 2026 using public company data. The primary goal was to identify whether the decrease could be attributed to specific stations, station types, or time periods, and to determine whether any rider subgroups were disproportionately affected.

The analysis combines SQL for data extraction and aggregation with Python for data cleaning, visualization, and statistical testing.

## Key Findings

- Total ridership declined by 24.2% from 2025 to 2026.
- The decrease was observed generally uniformly across nearly all station categories and time periods, with no obvious culprits.
- February had the largest decline of ridership, with the number of rides falling by 43%, suggesting that weather may be a key factor in the drop. 
- Morning ridership experienced the largest decline, suggesting weather or commuting behavior may play a role.
- Some stations experienced substantially larger losses than others, though no single station fully explained the overall decrease.
- Station-size groups (Small, Medium, Large, and Major Hub) all experienced similar declines.
- A Chi-Square Test of Independence found statistically significant differences between station-size groups; however, Cramér's V = 0.0108 indicated a negligible practical effect size, suggesting station size was not a meaningful driver of the decline.

## Tools & Technologies

- SQL – Data extraction and aggregation
- Python
  - pandas
  - numpy
  - matplotlib
  - scipy
- Google Colab – Host of analysis and reporting

## Future Work

While the analysis identified a widespread decline in ridership, it did not reveal a single dominant cause. Several additional data sources could provide valuable insight:

- Ride pricing information
- Distribution of ride costs
- Detailed weather data
- Construction and infrastructure changes
- Traffic patterns
- Geospatial route analysis using ride origins and destinations

These factors may help explain the decrease in demand observed across the Citi Bike network.

## Author

Luke Zingg

Applied Mathematics, Arizona State University

Interests: Data Science, Statistical Modeling, Data Visualization, and Data Analytics
