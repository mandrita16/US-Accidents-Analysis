# US Accidents Analysis

## Overview

This project performs Exploratory Data Analysis (EDA) on the US Accidents dataset obtained from Kaggle. The objective is to analyze accident patterns across the United States and discover insights related to accident severity, geographical distribution, time trends, and environmental factors.

The project uses Python-based data analytics and visualization libraries to identify accident hotspots and understand the factors contributing to road accidents.

---

## Dataset

Source:
https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents

Dataset Name:
US Accidents Dataset

Dataset Size:
- Millions of accident records
- Multiple years of accident data
- Covers all major US states

Key Features:

- ID
- Severity
- Start_Time
- End_Time
- Start_Lat
- Start_Lng
- End_Lat
- End_Lng
- Distance(mi)
- Description
- Street
- City
- County
- State
- Zipcode
- Weather Conditions
- Sunrise/Sunset
- Timezone
- Visibility
- Temperature
- Humidity
- Wind Speed

---

## Objectives

- Analyze accident severity distribution.
- Identify accident-prone states and cities.
- Study temporal accident trends.
- Analyze accident frequency by hour, day, and month.
- Explore weather-related accident patterns.
- Visualize geographical accident hotspots.
- Detect missing values and data quality issues.

---

## Technologies Used

### Programming Language
- Python

### Libraries

#### Data Processing
- Pandas
- NumPy

#### Data Visualization
- Matplotlib
- Seaborn
- Plotly

#### Geospatial Analysis
- GeoPandas
- GeoPlot
- Geopy

#### Data Quality Analysis
- Missingno

#### NLP Utilities
- NLTK

---

## Project Workflow

### 1. Dataset Collection

The dataset is downloaded directly from Kaggle using:

```python
import opendatasets as od

od.download("https://www.kaggle.com/sobhanmoosavi/us-accidents")
