# US Accidents Analysis

## Overview

This project performs Exploratory Data Analysis (EDA) on the US Accidents dataset obtained from Kaggle. The goal is to identify accident patterns, severity trends, geographical hotspots, and temporal insights across the United States using data analytics and visualization techniques.

---

## Dataset

**Source:** https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents

The dataset contains millions of accident records collected from multiple traffic and transportation sources across the United States.

### Important Features

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
- Country
- Timezone

---

## Project Objectives

- Analyze accident severity distribution.
- Identify accident-prone states and cities.
- Discover peak accident hours and days.
- Study accident trends over time.
- Explore geographic accident hotspots.
- Understand data quality and missing values.
- Create informative visualizations for decision-making.

---

## Tech Stack

### Programming Language
- Python

### Libraries Used

#### Data Analysis
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

### 1. Dataset Collection

Dataset downloaded directly from Kaggle using OpenDatasets:

```python
import opendatasets as od

od.download("https://www.kaggle.com/sobhanmoosavi/us-accidents")
```

### 2. Data Loading

```python
import pandas as pd

df = pd.read_csv("US_Accidents_Dec20_Updated.csv")
```

### 3. Data Cleaning

- Handling missing values
- Removing duplicate records
- Checking data types
- Data preprocessing

### 4. Exploratory Data Analysis

#### Severity Analysis
- Accident severity distribution
- High-risk accident categories

#### Location Analysis
- State-wise accident distribution
- City-wise accident distribution
- County-wise accident analysis

#### Time Analysis
- Hourly accident trends
- Monthly accident trends
- Day-wise accident patterns

#### Geographic Analysis
- Latitude-Longitude mapping
- Accident hotspot identification
- Regional accident density

### 5. Visualization

Created visualizations using:
- Matplotlib
- Seaborn
- Plotly

Visualization types:
- Bar Charts
- Pie Charts
- Scatter Plots
- Heatmaps
- Geographic Maps
- Interactive Dashboards

---

## Project Structure

```text
US-Accidents-Analysis/
│
├── Analysis_of_US_Accidents.ipynb
├── README.md
├── requirements.txt
│
├── dataset/
│   └── US_Accidents_Dec20_Updated.csv
│   
└── reports/
    └── project_report.pdf
```

---

## Installation

### Clone Repository

```bash
git clone https://github.com/mandrita16/US-Accidents-Analysis.git
```

### Move into Project Directory

```bash
cd US-Accidents-Analysis
```

### Install Dependencies

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

- Accident occurrences are concentrated in highly populated urban regions.
- Certain states consistently report higher accident frequencies.
- Peak traffic hours show increased accident rates.
- Accident severity varies across different locations.
- Geographic visualization helps identify accident-prone zones.

---

## Future Enhancements

- Accident Severity Prediction using Machine Learning
- Power BI Dashboard Integration
- Streamlit Web Application
- Real-Time Traffic Accident Analysis
- Interactive Geospatial Dashboard

---

## Learning Outcomes

- Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Geospatial Analytics
- Data Visualization
- Large Dataset Handling
- Insight Generation from Real-World Data

---

## Author

Mandrita Dasgupta

Data Analytics | Python | Data Visualization | Geospatial Analytics
