# Health Insurance Cost Drivers Analysis

## Overview

This project analyzes employee medical insurance charges to identify the primary cost drivers behind a recent **15% premium increase**. The goal was to uncover actionable insights for targeted wellness campaigns to help reduce per-employee costs.

## Key Findings

- **Smoking status** is the strongest predictor, explaining ~**62%** of variability in charges.
- **Age** contributes a steady increase (~9% explained variance).
- **BMI** alone shows minimal impact for non-smokers.
- **Critical interaction**: Smokers with BMI ≥30 experience exponentially higher charges (e.g., from ~$21k at BMI 25 to ~$35k at BMI 35 for a 30-year-old).

## Project Structure

- `data/`          → raw & processed datasets
- `notebooks/`     → Jupyter notebooks (numbered by analysis stage)
- `reports/figures/` → key charts for presentation

## Notebooks

- [01_data_exploration.ipynb](notebooks/01_data_exploration.ipynb) – Data loading & cleaning
- [02_eda_and_visualization.ipynb](notebooks/02_eda_and_visualization.ipynb) – Scatter plots & correlations
- [03_modeling_and_scenarios.ipynb](notebooks/03_modeling_and_scenarios.ipynb) – Lasso regression & what-if scenarios

For the complete story, visuals, business recommendations, and executive-style presentation → check out the [Notion Project Page](https://www.notion.so/Health-Insurance-Cost-Drivers-Analysis-322b7682d7a780be93dfda917e97018d).
