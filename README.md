# Telecom Churn & Revenue Dashboard

**WGU MSDA D211 | Jared Medlin | March 2025**

## Overview

An interactive Tableau dashboard comparing churn rate and Average Revenue 
Per User (ARPU) across two telecom datasets, with state-level filtering 
and a colorblind-friendly design.

## Key Findings

- Nationally, the company had higher churn and higher monthly charges 
  than the comparison dataset
- In California, churn rate was lower despite similar monthly charges, 
  suggesting regional factors beyond pricing drive churn
- Monthly charge alone is not a reliable predictor of churn behavior

## Dashboard Features

- Churn rate comparison (bar chart)
- ARPU comparison across both datasets
- Monthly charge distribution (histogram) for both datasets
- State filter toggle — supports multi-state selection

## How to Open

1. Download and install [Tableau Desktop](https://www.tableau.com/products/desktop) 
   or [Tableau Public](https://public.tableau.com/app/discover) (free)
2. Open `D211-2.twbx` directly in Tableau
3. Use the state filter on the right side to explore by region
4. Navigate between views using the caption tabs at the top of the Story pane
5. Press **F7** for presentation mode

## Tools Used

- Tableau Desktop & Tableau Prep
- PostgreSQL (pgAdmin) for initial data ingestion
- SQL for schema creation and data import

## Data Source

[Telecom Churn Dataset](https://www.kaggle.com/datasets/mnassrib/telecom-churn-datasets) 
— Kaggle

## Repository Contents

| File | Description |
|------|-------------|
| `D211-2.twbx` | Tableau packaged workbook (dashboard + data) |
