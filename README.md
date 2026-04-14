# Groundwater Level Forecasting in Kazerun Aquifer – Adaptive Ensemble Framework

This repository contains all R and Python scripts for reproducing the results presented in the paper:  
*"Groundwater Level Forecasting in a Complex Semi‑Arid Aquifer Using an Adaptive Ensemble Framework"* (Earth Science Informatics, 2026)

## Contents

| File | Description |
| :--- | :--- |
| `scripts/01_HBARST.R` | Hierarchical Bayesian spatio-temporal model (HBARST) |
| `scripts/02_SARIMA_auto.R` | Automated SARIMA model selection (SPSS Expert Modeler) |
| `scripts/03_SARIMA_manual.R` | Manually tuned SARIMA following Box‑Jenkins |
| `scripts/04_ensemble_weights.py` | Inverse-RMSE ensemble weighting |
| `scripts/05_machine_learning_benchmarks.py` | Random Forest, XGBoost, CatBoost, LightGBM, LSTM with Bayesian optimization |
| `scripts/06_wavelet_analysis.py` | Wavelet multi-resolution decomposition (Daubechies‑4) |
| `scripts/07_scenario_analysis.R` | Management scenarios and SDG 13 indicators |

## Requirements

**R (≥ 4.0)** with packages:
```r
install.packages(c("spTimer", "forecast", "ggplot2", "dplyr", "tidyr"))
