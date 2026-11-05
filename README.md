# Experiment 6 — Machine Learning Forecasting Using Regression and Tree-Based Models

**Course:** Time Series Analysis and Forecasting  
**Course Code:** CS3216  
**Student:** Chetana S  
**USN:** 1RUA24CSE0107  
**Experiment Date:** 05-11-2026

## Aim
Develop and evaluate regression and tree-based machine-learning forecasting models by converting a time series into a supervised-learning dataset using lag and rolling features.

## Notebook
Open `Experiment_6_ML_Forecasting_Chetana_S.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab and run the cells from top to bottom.

## Requirements
- Python 3.x
- NumPy
- pandas
- Matplotlib
- scikit-learn
- XGBoost (optional)

Install dependencies:

```bash
pip install -r requirements.txt
```

## Models
1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. XGBoost (optional)

## Method
- Lag features: 1, 2 and 3 previous observations
- Rolling feature: shifted 3-period rolling mean
- Train-test split: chronological 80:20, without shuffling
- Evaluation: MAE, RMSE and MAPE

## Reproducibility
The experiment uses the 36 monthly demand values supplied in the laboratory handout. The first three rows are removed after feature generation because lag/rolling features are unavailable. Thus, 33 rows remain: 26 training rows and 7 test rows.

## Expected metrics for the three required models
| Model | MAE | RMSE | MAPE (%) |
|---|---:|---:|---:|
| Linear Regression | 10.36 | 12.30 | 2.92 |
| Decision Tree | 47.96 | 51.74 | 13.61 |
| Random Forest | 41.57 | 45.88 | 11.75 |

Metrics may vary if the model settings or dataset are changed.

## GitHub
After creating your GitHub repository, add its URL here:
`[Paste your repository URL]`
