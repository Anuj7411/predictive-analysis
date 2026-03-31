# Predictive Analysis

This project analyzes historical product demand and explores demand forecasting plus inventory optimization using Jupyter notebooks.

## Project Files

- `PredictiveAnaOptimized.ipynb`: the cleaner, fully validated notebook for forecasting and optimization.
- `PredictiveAnalysis.ipynb`: the original exploratory notebook with EDA, modeling, and optimization sections.
- `Historical Product Demand.csv`: source dataset used by the notebooks.
- `data_processed.csv`: processed dataset generated from the source data.

## What The Project Does

- cleans and profiles historical demand data
- analyzes trends across products and warehouses
- compares simple forecasting and ML models
- solves inventory optimization problems using PuLP
- performs scenario and sensitivity analysis

## Setup

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter:

```bash
jupyter notebook
```

Then open either notebook in the project folder.

## Validation Status

- `PredictiveAnaOptimized.ipynb` was executed successfully in this environment after installing `PuLP`.
- `PredictiveAnalysis.ipynb` was checked and fixed for a missing `train_test_split` import in the model-training section.

## Notes

- The CSV files are large, so pushing the repository to GitHub may take a little time.
- If you want a lighter repository, you can keep only the notebooks and add the datasets separately later.
