# Used Car Price Drivers 
CRISP‑DM analysis of Kaggle used‑car listings to model price drivers with Linear/Ridge/Lasso regression and feature importance.

## Overview
This project analyzes a Kaggle used‑car dataset to identify the main drivers of vehicle prices. It follows the CRISP‑DM framework and builds regression models (Linear, Ridge, Lasso) to deliver interpretable insights for a used‑car dealership.

## Contents
- Main notebook: [prompt_II.ipynb](prompt_II.ipynb)

## Key Steps
- Data cleaning and deduplication (VIN-based)
- Feature engineering (e.g., vehicle age)
- Modeling with cross‑validation
- Evaluation in dollar terms (RMSE/MAE)
- Feature importance visualization (Lasso)
- Final Report

## How to Run
1. Open [prompt_II.ipynb](prompt_II.ipynb)
2. Run cells top‑to‑bottom
3. Plots are saved to `figures/`

## Dependencies
- Python 3.x
- pandas, numpy
- scikit‑learn
- matplotlib, seaborn, plotly
