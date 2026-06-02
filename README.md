# Anantapur Wind Energy Potential Analysis

## Overview

This project evaluates the wind energy potential of Anantapur, Andhra Pradesh, using NASA POWER climate data. Through time-series analysis, seasonal trend identification, and wind power estimation, the study explores the feasibility of wind energy generation in an emerging renewable energy region.

## Objectives

* Analyze daily and monthly wind speed patterns in Anantapur.
* Identify seasonal trends affecting wind energy generation.
* Estimate wind power output using wind speed data.
* Compare wind speeds at different heights (10m and 50m).
* Evaluate the suitability of Anantapur for future wind energy development.

## Dataset

The dataset was obtained from the NASA POWER database using the coordinates of Anantapur (14.68°N, 77.60°E).

### Variables Used

* WS50M – Wind Speed at 50 meters
* WS10M – Wind Speed at 10 meters
* T2M – Temperature at 2 meters

### Time Period

* Daily observations for the year 2025

## Methodology

1. Collected climate data from NASA POWER.

2. Cleaned and structured the dataset for time-series analysis.

3. Created a unified date variable from year, month, and day fields.

4. Calculated estimated wind power output using the wind power relationship:

   Power ∝ Wind Speed³

5. Performed trend analysis and seasonal aggregation.

6. Conducted correlation analysis between wind speed, temperature, and power output.

7. Visualized patterns using line plots, bar charts, and heatmaps.

## Key Findings

### Seasonal Wind Patterns

* Wind speeds increase significantly during the monsoon season.
* Peak wind activity occurs during June and July, with monthly average speeds approaching 9–10 m/s.
* Wind speeds remain relatively stable during the remainder of the year.

### Wind Power Potential

* Estimated power output rises sharply during high-wind periods due to the cubic relationship between wind speed and power.
* Small increases in wind speed produce disproportionately larger energy output.

### Height-Based Analysis

* Wind speeds at 50 meters are consistently higher than those at 10 meters.
* Higher turbine hub heights can substantially improve energy generation efficiency.

### Correlation Insights

* Wind speed at 50m and 10m show a very strong positive correlation (≈ 0.99).
* Wind speed and estimated power output show a strong positive relationship (≈ 0.94).
* Temperature has minimal influence on wind energy generation in this analysis.

## Conclusion

The analysis indicates that Anantapur possesses strong potential for wind energy generation, particularly during monsoon months when wind speeds are highest. The findings suggest that with suitable infrastructure, energy storage systems, and hybrid renewable energy integration, the region could emerge as an important wind energy hub in India.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* NASA POWER API
* Time Series Analysis

## Repository Contents

* Jupyter Notebook
* Dataset
* Project Report
* Visualizations

## Author

Asmita Baul

B.Sc. Data Science & Analytics
