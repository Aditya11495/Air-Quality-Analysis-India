# Project Overview

Air pollution is one of the major environmental challenges affecting public health.
This project analyzes India's air quality dataset to understand pollution trends, AQI levels, and the contribution of various pollutants.

The analysis was performed using **Python for data cleaning and preprocessing** and **Power BI for interactive dashboard visualization**.

# Dataset

The dataset contains air pollution measurements across multiple Indian cities.

Key variables include:

* City
* Date
* PM2.5
* PM10
* NO
* NO2
* NOx
* NH3
* CO
* SO2
* O3
* Benzene
* Toluene
* AQI
* AQI Bucket

---

# Project Workflow

# 1 Data Cleaning (Python)

Using pandas:

* Removed or handled missing values
* Imputed numerical columns using median values
* Cleaned AQI and pollutant data
* Exported cleaned dataset

# 2 Exploratory Data Analysis

Key insights explored:

* AQI trends across cities
* Pollution level variations
* Distribution of AQI categories
* Pollutant concentration patterns

---

# 3 Data Visualization (Power BI)

An interactive dashboard was created to visualize:

* Average AQI by city
* AQI trends over time
* Distribution of AQI categories
* Pollutant concentration comparison

---

## Tools & Technologies

* Python
* Pandas
* Power BI
* GitHub

---

## Project Structure

```
Air-Quality-Analysis-India
│
├── data
│   ├── air_quality_raw.csv
│   └── air_quality_cleaned.csv
│
├── notebooks
│   └── data_cleaning.ipynb
│
├── dashboard
│   └── air_quality_dashboard.pbix
│
├── images
│   └── dashboard_preview.png
│
└── README.md
```

## Dashboard Preview

(Add screenshot of Power BI dashboard here0

## Key Insights

* Some cities show consistently high AQI levels.
* PM2.5 and PM10 contribute significantly to poor air quality.
* AQI levels fluctuate across seasons and cities.


## Author

Aditya Singh
Aspiring Data Scientist / Data Analyst
