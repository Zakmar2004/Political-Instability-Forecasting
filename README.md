# Political Instability Forecasting

This repository contains the code for the coursework "Forecasting Political Instability Using Machine Learning Methods" by Ullubiy Zabitov, completed in May 2025. The project develops an interpretable machine learning model to predict political instability using the Political Instability Task Force (PITF) dataset.

## Project Overview

The goal of this study is to forecast political instability in high-risk states, using logistic regression. The model balances predictive accuracy with interpretability. Key innovations include:

- Multi-horizon forecasting: Predictions for 1, 2, and 5-year horizons with robust performance (AUPRC: 0.166–0.190).
- Regional conflict effects: Incorporation of nc4 (conflict in ≥4 neighboring states) to capture spillover dynamics.
- Interpretability: Use of SHAP values and logistic regression coefficients to provide global and local insights into instability drivers, such as factional democracies and socio-economic conditions.
- Rigorous validation: An expanding window validation strategy to simulate real-world forecasting scenarios.

The code, implemented in a single Jupyter Notebook (Political_Instability_Forecasting.ipynb), covers exploratory data analysis (EDA), model training, evaluation, and feature importance analysis, with case studies on Pakistan (2003) and Venezuela (2016).

## Usage

Open the Political_Instability_Forecasting.ipynb notebook and run all cells sequentially.

## Data

The analysis uses the PITF dataset compiled by Baillie et al. (2021). Please download it from https://osf.io/3gr72/.

## Coursework

The full coursework document, detailing the methodology, results, and discussion, is available as a PDF: [Forecasting_political_instability_using_machine_learning_methods.pdf](Forecasting_political_instability_using_machine_learning_methods.pdf).

## Acknowledgments

- Baillie et al. (2021) for providing the cleaned PITF dataset.
- The Political Instability Task Force for the original data collection.