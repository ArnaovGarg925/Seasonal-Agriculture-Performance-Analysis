# Seasonal Agriculture Performance Analysis

VOIS AICTE Batch1 2026-2027 — Major Project

Analyzing how agricultural yield, cost, revenue, profit, water efficiency and
disease/pest risk vary across the **Kharif, Rabi and Zaid** cropping seasons in
India, using a farm-level dataset of 4,000 records across 8 states, 8 crops and
4 irrigation methods.

## Problem Statement

Agricultural activities are influenced by seasonal variations in environmental
conditions, farming practices, resource availability and market conditions. This
project analyzes the dataset to identify meaningful seasonal patterns, trends,
relationships and differences in agricultural performance, and translates the
findings into evidence-based recommendations for seasonal agricultural planning.

## Contents

| File | Description |
|---|---|
| `Seasonal_Agriculture_Performance_Analysis.ipynb` | Full analysis notebook — data cleaning, EDA, visualizations, ANOVA significance testing, insights & recommendations |
| `seasonal_agriculture_performance_dataset.csv` | Source dataset (4,000 farm records, 28 columns) |
| `Seasonal_Agriculture_Performance_Analysis_PPT.pptx` | Project presentation |
| `requirements.txt` | Python packages needed to run the notebook |

## How to Run

```bash
pip install -r requirements.txt
jupyter notebook Seasonal_Agriculture_Performance_Analysis.ipynb
```

## Key Techniques Used

- Data cleaning: missing-value imputation (season/crop-wise median), IQR-based
  outlier capping
- Exploratory Data Analysis: season-wise summary statistics
- Visualizations: bar charts, boxplots, violin plots, heatmaps, scatter plots
- Statistical testing: one-way ANOVA (yield and profit across seasons)
- Correlation analysis of environmental and economic variables

## Author

**Arnav Garg**
B.Tech CSE Core, SRM Institute of Science and Technology (SRMIST), Modinagar
