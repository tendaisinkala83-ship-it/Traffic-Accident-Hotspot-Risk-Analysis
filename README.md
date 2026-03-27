# Traffic-Accident-Hotspot-Risk-Analysis

## Project Overview

This project analyzes traffic accident data to identify geographic hotspots and key risk patterns. The goal is to understand where and when accidents occur most frequently, and to uncover factors contributing to accident severity. Using Python-based analysis and geospatial visualization, the project highlights accident clustering and provides insights into real-world transportation risk.

## Objectives

- Identify high-risk geographic locations for traffic accidents
- Analyze temporal patterns in accident occurence
- Explore factors influencing accident severity
- Visualize accident hotspots using geospatial mapping
- Support data-driven approaches to road safety and planning

## Tools & Technologies

- **Python**
- **Pandas & NumPy**
- **Matplotlib**
- **Folium (Geospatial Mapping)**
- **Jupyter Notebook**

## Project Structure
```
  traffic-risk-analysis/
             notebooks/
                01_data_cleaning.ipynb
                02_exploratory_analysis.ipynb
                03_geospatial_mapping.ipynb
                04_severity_prediction.ipynb
             outputs/
               cleaned_accidents.csv
               accident_heatmap.html

             README.md
```

## Key Analysis Steps

### 1. Data Cleaning & Preparation
- Reduced dataset size for efficient analysis
- Selected relevant geographic, temporal, and environmental variables
- Handled missing values and ensured valid coordinate data
- Engineered time-based features (hour, day, month)

### 2. Exploratory Data Analysis
- Analyzed accident distribution by severity
- Identified peak accident hours and high-risk days
- Examined geographic variation across states
- Explored patterns in environmental conditions

### 3. Geospatial Analysis
- Created interactive maps using Folium
- Visualized accident locations using coordinate data
- Built heatmaps to identify accident hotspots
- Highlighted clustering in major urban and high-traffic areas

### 4. Severity Analysis
- Explored factors contributing to accident severity
- Identified relationships between environmental conditions and accident outcomes
- Prepared data for potential predictive modeling

## Key Insights

- Traffic accidents are highly concentrated in urban areas and along major road networks
- Accident frequency peaks during commuting hours
- Geographic clustering indicates strong correlation with population density and traffic volume
- Severity patterns suggest environmental and visibility conditions influence accident outcomes

## Business Impact

This analysis demonstrates how geospatial data can support:
- Road safety improvement strategies
- Urban planning and traffic management
- Risk assessment for transportation systems
- Data-driven decision-making in public infrastructure

## Dataset

US Accidents Dataset (2016-2023)
Avaliable on Kaggle

## Interactive Map

An interactive accident heatmap is included in the `outputs` folder:

outputs/accident_heatmap.html

This file can be opened in a browser to explore accident hotspots dynamically.

## Author

**Tendai Sinkala**
Data Analyst | SQL - Python - Machine Learning - Geospatial Analytics

## Future Improvements

- Build predictive model for accident severity
- Incorporate real-time traffic data
- Add geographic clustering algorithms
- Develop interactive dashboard for stakeholders


