# Project Management Analytics Case Study

This repository contains a synthetic project management dataset and accompanying analysis designed for aspiring business analysts, program managers, and data analysts. It showcases how to perform exploratory data analysis (EDA) and build predictive models to gain insights from project data.

## Dataset

The dataset (`project_management_synthetic_data.csv`) contains 200 rows of simulated project observations with the following columns:

| Column              | Description                                                       |
|---------------------|-------------------------------------------------------------------|
| TeamSize            | Number of people assigned to the project (integer).              |
| Budget             | Project budget in USD (float).                                   |
| DurationDays        | Project duration in days (integer).                              |
| RiskLevel           | Categorical variable indicating project risk level (Low/Medium/High). |
| Complexity          | Complexity of the project on a scale of 1–10 (integer).          |
| Industry            | Industry sector (Finance, Healthcare, Technology, Retail, Manufacturing). |
| ClientSatisfaction  | Synthetic client satisfaction rating on a scale of 1–10 (float). |
| Outcome             | Binary target variable: 1 = Project delivered successfully, 0 = otherwise. |

The dataset is **synthetic**—created using random numbers with simple rules to simulate realistic project dynamics. It does not contain any confidential or real-world data.

## Analysis

The `project_management_analysis.ipynb` notebook performs the following steps:

1. **Loading and inspecting the data** to understand its structure and basic statistics.
2. **Exploratory data analysis**, including distribution plots, risk-level comparisons, and a correlation heatmap.
3. **Data preprocessing** with scaling and one-hot encoding of categorical variables.
4. **Model training** using logistic regression and random forest classifiers to predict project success.
5. **Model evaluation** using accuracy scores, classification reports, and confusion matrices.
6. **Conclusions** summarizing key findings about factors influencing project outcomes.

This project can serve as a template for demonstrating analytical skills to potential employers. Feel free to extend the analysis, tune models, or add new features.

## Getting Started

1. Clone this repository or download the source.
2. Install the required dependencies (see `requirements.txt`). It's recommended to use a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scriptsctivate`
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook project_management_analysis.ipynb
   ```
4. Explore the notebook, run the cells, and review the analysis.

## Requirements

See [`requirements.txt`](requirements.txt) for the list of Python packages needed to run the notebook.

## License

This project is licensed under the MIT License. You are free to use, modify, and distribute it for educational or professional purposes.

## About

Created as part of a portfolio-building exercise for business analysts, program managers, and data analysts seeking to demonstrate data exploration and predictive modeling skills on a synthetic project management dataset.


## Notes

This update demonstrates a pull request workflow by adding a notes section to the README.
