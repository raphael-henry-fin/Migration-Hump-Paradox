# Migration-Hump-Paradox
Does foreign aid reduce emigration?
An econometric study of the Migration Hump Paradox across 120 developing countries, using Gretl

Joint project with Julian Ansarinasab — Université Paris-Dauphine, December 2025.

## Key results

* **Model Type:** Econometric panel data / OLS estimation and model selection diagnostics.
* **Core Focus:** Testing the non-linear relationship between economic development (and foreign aid) and international emigration.
* **Methodology:** Step-by-step econometric validation, OLS regressions, diagnostic testing for residuals, multicollinearity, and heteroskedasticity.

## Repository structure

* `report/` — final PDF research papers (`part1_ols_estimation.pdf` & `part2_model_selection_diagnostics.pdf`)
* `src/migration_hump.inp` — full Gretl script containing all econometric commands and estimations
* `data/` — raw and processed datasets used for the analysis (Net Migration, Population, Net ODA, GDP per capita, Youth Unemployment, Political Stability)

## Methods

Ordinary Least Squares (OLS) estimation, multicollinearity checks (VIF), residual normality and heteroskedasticity tests, model selection criteria (AIC/BIC).

## Requirements

* [Gretl](http://gretl.sourceforge.net/) (GNU Regression, Econometrics and Time-series Library)
