# US Traffic Accident Analytics

## Overview

Road traffic accidents are a major public safety concern worldwide. Understanding accident patterns can help authorities, transportation agencies, and urban planners improve road safety and reduce accident risks.

This project performs Exploratory Data Analysis (EDA) on the US Accidents Dataset, a large-scale traffic accident dataset containing approximately 7.7 million accident records collected across 49 US states between February 2016 and March 2023.

The analysis focuses on identifying accident trends, severity patterns, weather impacts, temporal variations, and geographical hotspots using Python-based data analytics and visualization techniques.

---

## Dataset Information

### Dataset Source

US Accidents Dataset

https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents

### Dataset Statistics

- Coverage: 49 US States
- Time Period: February 2016 – March 2023
- Total Records: Approximately 7.7 Million
- Data Sources:
  - US Department of Transportation
  - State Transportation Agencies
  - Traffic Cameras
  - Traffic Sensors
  - Law Enforcement Agencies

---

## Project Objectives

- Analyze accident severity distribution.
- Identify accident-prone states and cities.
- Study accident frequency across different time periods.
- Investigate the influence of weather conditions on accidents.
- Examine geographical accident hotspots.
- Analyze road infrastructure factors contributing to accidents.
- Generate meaningful insights using visual analytics.

---

## Features Analyzed

### Accident Information

- Severity
- Start Time
- End Time
- Distance
- Description

### Geographical Information

- Latitude
- Longitude
- City
- County
- State
- Zipcode

### Weather Information

- Temperature
- Humidity
- Pressure
- Visibility
- Wind Speed
- Precipitation
- Weather Condition

### Road Infrastructure Features

- Crossing
- Junction
- Railway
- Stop
- Traffic Signal
- Roundabout
- Station
- Traffic Calming

### Time Features

- Sunrise/Sunset
- Civil Twilight
- Nautical Twilight
- Astronomical Twilight

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

#### Dataset Access

- Kaggle API
- OpenDatasets

---

## Project Workflow

### 1. Importing the Necessary Libraries

The project begins by importing Python libraries required for data manipulation, visualization, geospatial analysis, and statistical exploration.

### 2. Dataset Collection

Downloaded the dataset directly from Kaggle using Kaggle API and OpenDatasets.

### 3. Data Loading

Loaded accident records into Pandas DataFrames for processing and analysis.

### 4. Data Cleaning

- Missing value analysis
- Data preprocessing
- Duplicate handling
- Data validation

### 5. Exploratory Data Analysis

#### Severity Analysis

- Accident severity distribution
- Severity comparison

#### Temporal Analysis

- Hourly accident trends
- Daily accident trends
- Monthly accident trends

#### Geographical Analysis

- State-wise accident distribution
- City-wise accident distribution
- Accident hotspot identification

#### Weather Analysis

- Weather condition impact
- Visibility analysis
- Environmental factor analysis

### 6. Data Visualization

Created visualizations using:

- Matplotlib
- Seaborn
- Plotly

Visualization Types:

- Histograms
- Bar Charts
- Scatter Plots
- Heatmaps
- Interactive Visualizations
- Geographic Analysis Charts

---

## Project Structure

```text
US-Traffic-Accident-Analytics/
│
├── Analysis_of_US_Accidents.ipynb
├── Analysis_of_US_Accidents_Report.pdf
├── requirements.txt
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/US-Traffic-Accident-Analytics.git
```

Move into the project directory:

```bash
cd US-Traffic-Accident-Analytics
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Requirements

```txt
pandas
numpy
matplotlib
seaborn
plotly
missingno
geopandas
geoplot
geopy
nltk
opendatasets
kaggle
```

---

## Key Insights

- Accident occurrences vary significantly across states and cities.
- Severe accidents are concentrated in major transportation corridors.
- Adverse weather conditions increase accident risk.
- Peak traffic hours experience higher accident frequencies.
- Urban regions show greater accident density than rural regions.
- Geospatial analysis helps identify accident-prone zones.

---

## Future Improvements

- Accident Severity Prediction using Machine Learning
- Real-Time Traffic Monitoring Dashboard
- Power BI Integration
- Streamlit Deployment
- Predictive Accident Risk Analysis

---

## Learning Outcomes

- Exploratory Data Analysis
- Data Cleaning and Preprocessing
- Data Visualization
- Geospatial Analytics
- Large-Scale Dataset Handling
- Insight Generation from Real-World Data

---

## Author

Mandrita Dasgupta

Data Analytics | Data Science | Machine Learning | Data Visualization
