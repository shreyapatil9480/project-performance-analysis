# Project Performance Analysis

This repository contains a synthetic dataset and analysis notebook tailored for business analysts, program managers, and data analysts. The project demonstrates an end-to-end workflow from data generation to exploratory data analysis and predictive modeling.

## Dataset

The `synthetic_project_data.csv` file contains 200 records representing projects across various domains. Each record includes the following fields:

- **ProjectID**: Unique identifier for each project
- **StartDate** & **EndDate**: Project start and end dates
- **DurationDays**: Planned duration of the project in days
- **Budget**: Allocated budget for the project
- **ActualCost**: Actual cost incurred
- **RiskLevel**: Categorical risk assessment (Low, Medium, High, Critical)
- **TeamSize**: Number of team members involved
- **ScopeComplexity**: Ordinal measure of complexity (1–5)
- **Domain**: Business domain (e.g., IT, Marketing, Finance)
- **Status**: Current project status (On Track, Delayed, Completed, Cancelled)
- **Success**: Binary label indicating whether the project met budget, avoided cancellation, and stayed within 30 days of planned completion

## Analysis Notebook

The `analysis.ipynb` notebook walks through the following steps:

1. **Load and explore the dataset**
2. **Descriptive statistics and visualizations**: Explore distributions of budgets, durations, and team sizes; visualize correlations; examine relationships between risk levels and other factors.
3. **Predictive modeling**: Build a logistic regression and a random forest classifier to predict project success based on available features. Evaluate models using accuracy and confusion matrices.

## Getting Started

To explore the notebook locally:

```bash
# Install dependencies
pip install -r requirements.txt

# Launch Jupyter and open analysis.ipynb
jupyter notebook
```

The notebook is self-contained and can be run end-to-end. Modify or extend the analysis as desired to demonstrate additional skills or techniques relevant to business analysis and program management.

## Contributing

You are welcome to fork this repository, create feature branches, and submit pull requests for improvements or additional analyses.

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
