# Store Sales Forecasting

## Overview

This project predicts product sales using historical sales information and XGBoost.

## Methods

- Rolling Mean Features
- Lag Features
- TimeSeriesSplit
- XGBoost

## Result

Best CV RMSLE: 0.826

## Key Findings

The rolling_mean_7 feature was the most effective predictor in this experiment.

Additional lag and trend features did not improve model performance.

This project demonstrates the importance of feature engineering and cross validation.
## Result

Best CV RMSLE: 0.826

## Key Findings

- rolling_mean_7 achieved the best performance.
- Additional lag and trend features did not improve validation score.
- Cross validation was essential for comparing features fairly.

## Technologies

- Python
- Pandas
- NumPy
- XGBoost
- Scikit-learn
- Matplotlib
