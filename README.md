# Predicting Intensive Gambling Behavior Using Static and Temporal Behavioral Features

DS 340W research project examining whether temporal behavioral features improve prediction of later intensive gambling behavior beyond static aggregate features.

## Project Files

- `novel_analysis.Rmd` - Complete reproducible analysis and modeling code.
- `novel_analysis.html` - Rendered version of the analysis including tables and figures.
- `calcdata/` - Five SatoshiDice datasets used in the experiment.
- `renv.lock` - Exact R package environment used for the analysis.
- `sessionInfo.txt` - R and system information from the original experiment.

## Models

The project compares three feature representations:

- Static behavioral features
- Temporal behavioral features
- Combined static and temporal features

Three predictive models are evaluated:

- Logistic Regression
- Random Forest
- XGBoost

SHAP values are used to interpret the Combined XGBoost model.

## Reproducing the Analysis

1. Clone this repository.
2. Open `Novel_Implementation.Rproj` in RStudio.
3. Install the `renv` package if necessary:

   `install.packages("renv")`

4. Restore the package environment:

   `renv::restore()`

5. Open `novel_analysis.Rmd`.
6. Knit the document from top to bottom.

The original analysis was performed using R 4.6.2.
