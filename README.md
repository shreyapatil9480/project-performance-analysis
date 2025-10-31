[![Python CI](https://github.com/shreyapatil9480/project-performance-analysis/actions/workflows/python-ci.yml/badge.svg)](https://github.com/shreyapatil9480/project-performance-analysis/actions/workflows/python-ci.yml)
![Python](https://img.shields.io/badge/python-3.11-blue)
![pytest](https://img.shields.io/badge/tested%20with-pytest-0A9EDC)

# Project Performance Analysis

When do sales forecasts miss accuracy targets?

**Stakeholder:** Revenue Operations Analyst

## Key Insights

- Discounts above 20% degrade forecast accuracy in Q4.
- High seasonality regions need separate forecast models.
- West region forecasts are accurate 68% of the time at baseline.

## Dataset

Primary file: `data/sales_forecast.csv`  
Target variable: `forecast_accurate`

## Getting Started

```bash
pip install -r requirements.txt
jupyter notebook notebooks/01_exploration.ipynb
```



## Testing

```bash
pip install -r requirements.txt
pytest tests/ --cov=src
```

## Next Steps

Automate SQL exports into a weekly stakeholder report.

---
*Analytics portfolio project — 2025-08*

<!-- build 6 -->

### Implemented

```bash
pip install -r requirements.txt
python scripts/weekly_report.py
```
