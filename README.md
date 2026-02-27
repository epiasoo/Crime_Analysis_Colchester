# Spatio-Temporal Analysis of Crime Trends in Colchester (2024–2025)

This project presents a comprehensive spatio-temporal analysis of crime patterns in Colchester between 2024 and 2025, which examines how crime distribution varies across time, location, and environmental conditions. This integrates street-level crime data with local weather records to investigate whether climatic factors such as temperature, precipitation, humidity, and sunshine—influence criminal activity.

The analysis combines statistical modelling, geographic visualization, and interactive graphics to uncover seasonal trends, spatial hotspots, and environmental correlations affecting crime in the region.

---

## Project Objectives

- Analyze the temporal distribution of crime (daily and monthly trends)
- Identify dominant crime categories and case outcomes
- Detect geographic hotspots using spatial mapping
- Explore seasonal and weather-related influences on crime
- Examine the relationship between temperature and daily crime counts

---

## Datasets 

- Crime Data (2024–2025)
  - Crime type
  - Date
  - Latitude & longitude
  - Street name
  - Outcome status

- Weather Data (2023–2025)
  - Daily meteorological variables including:
  - Average, minimum, and maximum temperature
  - Precipitation
  - Humidity
  - Wind speed & gust
  - Sunshine duration
  - Cloud cover
 
  ---

## Key Analysis Components

### Crime Distribution Analysis
- Bar plots of crime categories (Violent Crime and Anti-Social Behaviour dominant)
- Pie chart of crime outcomes (large proportion unresolved or under investigation)
- Violin plot of daily crime spread (stable daily clustering)
- Monthly time-series trend with LOESS smoothing

### Spatial Analysis

- Interactive leaflet map of crime locations
- Identification of urban hotspots (town centre, commercial areas)
- Word cloud of frequent street/location descriptors

### Weather Analysis

- Year-over-year temperature comparison (2023–24 vs 2024–25)
- Density plots of average temperature
- Correlation matrix of meteorological variables
- Monthly averages of temperature, humidity, precipitation, and sunshine

### Crime & Temperature Relationship

- Scatter plot with regression line
- Positive correlation between temperature and daily crime counts
- Evidence of seasonal crime peaks during warmer months

---

## Key Findings

- Violent crime and anti-social behaviour are the most prevalent categories.
- Crime levels peak during summer months and decline in winter.
- Spatial clustering highlights higher crime concentration in central urban areas.
- Weather variables follow expected seasonal patterns.
- A positive association between temperature and crime frequency suggests environmental influence on criminal activity.

---

## Tools & Technologies
- R (tidyverse, ggplot2, leaflet, plotly, tm, wordcloud)
- Data visualization techniques (interactive plots, smoothing, clustering)
- Correlation analysis and regression modelling
- Geospatial mapping

---
