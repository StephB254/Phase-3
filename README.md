# Phase-3
Phase three project
# Predicting Water Well Failures in Tanzania

## Overview
This project analyzes Tanzanian water well data to predict well condition and identify the key drivers of well failure. The goal is to support better maintenance planning and resource allocation for water infrastructure.

## Business Problem
Many water wells in Tanzania are either non-functional or in need of repair. Stakeholders need a way to identify high-risk wells and prioritize interventions efficiently.

## Objectives
- Explore patterns associated with well failure
- Build classification models to predict well condition
- Translate model findings into actionable recommendations

## Data
The project uses the Tanzanian Water Wells datasets:
- training features
- training labels
- test features

## Methods
- Data cleaning and feature engineering
- Exploratory data analysis
- One-hot encoding for categorical variables
- Classification modeling using:
  - Dummy baseline
  - Decision Tree
  - Random Forest

## Key Insights
- Older wells are more likely to be non-functional
- Failure rates vary significantly by region
- Extraction system group is strongly associated with failure risk
- Random Forest performed best among the tested models

## Recommendations
- Prioritize maintenance for older wells
- Allocate more monitoring and repair resources to high-risk regions
- Review extraction system choices in areas with repeated failure

## Repository Structure
- `notebooks/` → Jupyter notebook
- `visuals/` → exported charts
- `data/` → local data storage (not pushed if ignored)
- `README.md` → project summary
- `requirements.txt` → project dependencies

## Author
Stephen Bwanamkubwa
