# statistical case studies

This repository contains a curated collection of case studies that demonstrate how to apply statistical theory to real-world data using Python.  The projects originated from coursework and personal research, and they cover topics such as hypothesis testing, regression, probability distributions, and data exploration.  The goal is two-fold: to **practice rigorous statistical analysis** on diverse datasets and to **engineer reproducible workflows** that others can run and extend.

## data science

- **Hypothesis testing** – formulates null and alternative hypotheses, performs t‑tests, chi‑square tests, and ANOVA on real datasets, and interprets p‑values and confidence intervals.
- **Regression modelling** – builds linear and logistic regression models to explore relationships between variables; performs diagnostic checks and regularization.
- **Case studies** – includes mini projects such as the Springboard regression case study, SQL-based data exploration, and pandas‑profiling for automated data summaries.
- **Exploratory data analysis** – cleans, visualizes, and summarizes datasets to inform model choices and identify outliers or data quality issues.

## ml engineering

- **Reproducible notebooks** – organizes Jupyter notebooks into topic‑specific folders and maintains them under version control for easy collaboration.
- **Modular scripts** – refactors notebook logic into Python modules (`linear_regression`, `project_7.2`, etc.) so analyses can be executed from the command line.
- **Environment and dependencies** – provides a `requirements.txt` file and example conda environment for installing the required Python libraries (numpy, pandas, statsmodels, scikit‑learn, etc.).
- **Automation** – uses a simple Makefile to run analysis pipelines and GitHub Actions to lint notebooks and ensure that the code runs without errors.

## repository structure

| path | purpose |
|------|---------|
| `Class/Notebooks/` | Jupyter notebooks covering topics such as frequentist inference, hypothesis testing and SQL. |
| `linear_regression/` | Python scripts and notebooks demonstrating simple and multivariate linear regression. |
| `project_7.2/` | A case study combining SQL queries with data analysis to answer business questions. |
| `pandas-profiling-master/` | Auto‑generated exploratory data analysis reports. |
| `dc/` | Miscellaneous datasets and utilities used across the case studies. |

## running the case studies

To run or view the analyses yourself:

1. Clone this repository:
   ```bash
   git clone https://github.com/Fam12345/statistical-case-studies-with-Python.git
   cd statistical-case-studies-with-Python
   ```
2. Create a Python environment and install dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```
3. Launch Jupyter Notebook or run a script:
   ```bash
   jupyter notebook
   # or run a specific script
   python linear_regression/simple_regression.py
   ```

These notebooks and scripts are intended as learning resources; they illustrate my approach to combining **statistical reasoning** with **software engineering** practices to produce transparent and reproducible analyses.
