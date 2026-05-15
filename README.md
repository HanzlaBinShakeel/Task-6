# Task 6: House Price Prediction

## Objective
Predict median house prices from property and geographic features.

## Dataset
**King County House Sales** (Kaggle-style CSV) — features include `bedrooms`, `sqft_living`, `bathrooms`, and location (`lat`, `long`).

## Models Applied
| Model | Evaluation |
|-------|------------|
| Linear Regression (scaled features) | MAE, RMSE, R² |
| Gradient Boosting Regressor | MAE, RMSE, R² |

## Key Results
- **MedInc** (median income) is the top predictor
- Gradient Boosting typically beats linear regression on RMSE
- Predicted vs actual scatter plots show strong alignment with some high-price tail error

## Files
| File | Description |
|------|-------------|
| `house_price_prediction.ipynb` | Full regression notebook |

## Run
```bash
jupyter notebook house_price_prediction.ipynb
```
