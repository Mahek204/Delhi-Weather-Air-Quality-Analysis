# Delhi Weather & Air Quality Analysis Using Python

## Project Overview

This project analyzes weather conditions and air quality patterns
in Delhi using Python.

The analysis combines weather parameters, air-quality indicators,
time-series information, and monitoring-station locations to
understand seasonal trends, pollution behavior, relationships
between meteorological variables and pollutants, and differences
across locations.

The project focuses on Exploratory Data Analysis (EDA), statistical
analysis, visualization, outlier detection, correlation analysis,
monthly trend analysis, and location-based analysis.

## Objectives

- Analyze weather patterns in Delhi
- Evaluate air quality using AQI and major pollutants
- Study relationships between weather parameters and pollution
- Identify seasonal and monthly patterns
- Analyze differences in air quality across monitoring stations
- Detect unusual and extreme observations
- Perform correlation analysis
- Visualize weather and pollution trends
- Generate meaningful environmental insights
- Provide recommendations based on the analysis

## Dataset

The dataset contains hourly weather and air pollution observations
from multiple monitoring locations in Delhi.

### Dataset Size

- Records: 52,566
- Variables: 16
- Frequency: Hourly
- Data Type: Time-series + spatial + environmental data

## Dataset Variables

### Temporal Variables

- date_ist
- time_ist

### Location Variables

- location
- lat
- lon

### Weather Variables

- temp_c
- humidity
- pressure_mb
- windspeed_kph
- condition_text

### Air Quality Variables

- aqi_index
- pm2_5
- pm10
- co
- no2

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Google Colab

## Data Preprocessing

The project includes several data-preparation steps:

1. Dataset inspection
2. Data type verification
3. Missing-value analysis
4. Duplicate-record identification
5. Date and time preparation
6. Outlier detection
7. Data aggregation for monthly analysis
8. Preparation of data for location-based comparisons

## Exploratory Data Analysis

The project analyzes the following areas:

### 1. Temperature Analysis

Temperature distributions and seasonal patterns are examined
using statistical summaries and visualizations.

### 2. Humidity Analysis

Humidity levels are analyzed to understand seasonal changes
and atmospheric moisture patterns.

### 3. Atmospheric Pressure Analysis

Pressure distributions and their relationship with other
meteorological variables are examined.

### 4. Wind Speed Analysis

Wind speed is analyzed because wind conditions influence
pollutant dispersion.

### 5. AQI Analysis

AQI levels are examined to identify pollution patterns
throughout the year.

### 6. PM2.5 Analysis

PM2.5 concentrations are analyzed to identify particulate
pollution levels and extreme pollution episodes.

### 7. PM10 Analysis

PM10 distribution and variability are studied to understand
coarse particulate pollution.

### 8. CO Analysis

Carbon monoxide concentrations are examined for variability
and high-pollution events.

### 9. NO2 Analysis

NO2 levels are analyzed to understand combustion-related
pollution patterns.

## Statistical Analysis

Statistical analysis includes:

- Mean
- Median
- Quartiles
- Standard deviation
- Distribution analysis
- Correlation analysis
- Outlier detection

## Outlier Detection

The Interquartile Range (IQR) method is used to identify
potential outliers.

The method uses:

Q1 = First Quartile

Q3 = Third Quartile

IQR = Q3 - Q1

Lower Bound = Q1 - 1.5 × IQR

Upper Bound = Q3 + 1.5 × IQR

Observations outside these limits are investigated as
potential outliers.

## Time-Series Analysis

Monthly and seasonal patterns are analyzed for:

- Temperature
- Humidity
- Atmospheric Pressure
- Wind Speed
- AQI
- PM2.5
- PM10
- CO
- NO2

## Location-Based Analysis

Air quality is compared across major monitoring locations:

- Anand Vihar
- Connaught Place
- Dwarka
- Okhla Phase III
- Rohini
- IGI Airport

## Correlation Analysis

Correlation analysis is used to examine relationships between
weather parameters and pollution indicators.

The analysis particularly examines:

- Temperature vs Pressure
- Temperature vs Humidity
- Temperature vs Wind Speed
- AQI vs PM2.5
- AQI vs PM10
- AQI vs CO
- AQI vs NO2

## Key Findings

### Weather Patterns

- Temperature shows clear seasonal variation.
- Temperatures increase from winter toward the summer months.
- Temperature decreases during the monsoon period and falls again
  during winter.
- Humidity increases during the monsoon period.
- Atmospheric pressure and temperature show a strong negative
  relationship.

### Air Quality

- AQI varies significantly across months and locations.
- Pollution levels are particularly severe during periods of
  stable atmospheric conditions.
- Monsoon months generally show improved air quality.

### Particulate Pollution

- PM2.5 and PM10 show substantial variability.
- Extreme particulate pollution episodes are present in the data.
- PM10 has a strong positive relationship with AQI.

### Location-Based Findings

- Anand Vihar records particularly high pollution levels.
- Okhla Phase III also experiences high particulate pollution.
- Dwarka generally shows comparatively better air quality.
- IGI Airport shows comparatively moderate pollution levels.

## Important Correlations

The analysis found:

- Temperature and pressure: approximately -0.68
- Temperature and humidity: approximately -0.51
- Temperature and wind speed: approximately 0.21
- Wind speed and humidity: approximately -0.25
- AQI and PM10: approximately 0.83
- AQI and PM2.5: approximately 0.52

The strong positive relationship between AQI and PM10 indicates
that particulate pollution is an important contributor to poor
air-quality conditions in the analyzed dataset.

## Monthly Pollution Pattern

The analysis identifies the following broad seasonal pattern:

- January: Cold and stable conditions with high pollution
- February: Pollution remains elevated
- March: Transitional weather with increasing pollution
- April: Hot and dry conditions
- May: Extreme heat with persistent pollution
- June: Monsoon influence begins and pollution declines
- July: Strong monsoon influence and lower pollution
- August: Continued rainfall and reduced pollution
- September: Post-monsoon transition
- October: Pollution begins increasing
- November: Severe pollution conditions
- December: Cold and stagnant conditions with high pollution

## Visualizations

The project includes:

- Distribution plots
- Box plots
- Violin plots
- Monthly trend charts
- Seasonal analysis
- Correlation heatmaps
- Location comparisons
- AQI analysis
- Pollutant analysis
- Weather parameter analysis

## Business and Policy Insights

The findings can support:

- Pollution-control planning
- Traffic-management strategies
- Industrial-emission monitoring
- Weather-based pollution warnings
- Public-health communication
- Location-specific pollution management
- Seasonal pollution preparedness

## Recommendations

Based on the analysis:

- Strengthen pollution-control measures in highly polluted areas.
- Improve traffic and congestion management.
- Monitor industrial emissions around high-pollution zones.
- Implement dust-control measures.
- Use weather-based early-warning systems during high-risk
  pollution periods.
- Encourage public transport during severe pollution episodes.
- Increase monitoring in locations with significant seasonal
  variation.

## Project Workflow

Data Collection
      ↓
Data Loading
      ↓
Data Understanding
      ↓
Data Cleaning
      ↓
Data Quality Checks
      ↓
Outlier Detection
      ↓
Exploratory Data Analysis
      ↓
Statistical Analysis
      ↓
Correlation Analysis
      ↓
Monthly & Seasonal Analysis
      ↓
Location-Based Analysis
      ↓
Visualization
      ↓
Insights & Recommendations
      ↓
Conclusion
