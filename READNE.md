# Delivery Food Analysis in Bangalore

## Overview
This project analyzes online food delivery patterns in Bangalore using a combination of Exploratory Data Analysis (EDA), geospatial visualization with ArcGIS, and basic modeling techniques. The goal is to derive insights into customer behavior, delivery hotspots, and geographic trends influencing the food delivery ecosystem in the city.

## Contents
- `data/`: Raw and cleaned datasets used for analysis
- `notebooks/`: Jupyter Notebooks for EDA and modeling
- `maps/`: ArcGIS geospatial layers and map visualizations
- `results/`: Output plots and summary files
- `README.md`: Project documentation

## Data Collection
The dataset was collected from multiple sources including:
- Publicly available food delivery data for Bangalore
- Restaurant location and customer order data
- API-based data for geolocation mapping (if applicable)

The data includes information on:
- Order frequency by location
- Delivery time
- Customer ratings
- Restaurant type and cuisine
- Delivery partner performance

## Exploratory Data Analysis (EDA)
Key steps in EDA:
- Visualized the distribution of orders by time, cuisine, and location
- Analyzed customer satisfaction scores and delivery delays
- Identified peak ordering hours and popular zones
- Used correlation heatmaps to examine relationships among variables

Tools used: `Pandas`, `Matplotlib`, `Seaborn`, `Plotly`

## ArcGIS Geospatial Analysis
Using ArcGIS, spatial analysis was performed to:
- Map restaurant density and delivery zones
- Identify delivery hotspots and underserved regions
- Overlay demographic data for market segmentation
- Generate interactive choropleth and heatmaps

Shapefiles and layers were imported into ArcGIS Pro and analyzed using spatial joins and buffer tools.

## Modeling
Applied basic modeling techniques to predict:
- Estimated delivery time based on location, traffic, and order volume
- Customer satisfaction prediction based on delivery experience

Models used:
- Linear Regression
- Decision Trees
- K-Nearest Neighbors (for classification tasks)

Evaluation Metrics:
- RMSE, R² for regression
- Accuracy, F1 Score for classification

## Results
- Identified top-performing zones and high-delay areas
- Demonstrated clear impact of distance and traffic density on delivery time
- Suggested zoning optimizations for delivery route efficiency
- Predicted satisfaction score trends with ~85% accuracy using delivery metrics

---
