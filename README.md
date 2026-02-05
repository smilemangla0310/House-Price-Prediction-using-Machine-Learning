# House Price Prediction using Machine Learning

A regression-based ML project to predict house prices using property features and compare multiple models.

## Features Used
- Area
- Bedrooms
- Bathrooms
- Age
- Location
- Property Type

## Models Implemented
- Linear Regression
- Polynomial Regression
- Decision Tree Regressor
- Random Forest Regressor

## Evaluation Metrics
- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- R² Score

## Results
Random Forest achieved the best performance with highest R² score (~0.97).

## Files
- `house_price_prediction.ipynb` — main notebook  
- `house_prices.csv` — dataset  
- `Model_Evaluation.md` — evaluation report  
- `predictions_vs_actual.png` — prediction plot  
- `requirements.txt` — dependencies  

## Run
```bash
pip install -r requirements.txt
jupyter notebook house_price_prediction.ipynb
