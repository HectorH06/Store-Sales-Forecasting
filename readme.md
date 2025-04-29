![Made with Python](https://forthebadge.com/images/badges/made-with-python.svg)
![Build with Love](http://ForTheBadge.com/images/badges/built-with-love.svg)

```ascii
███████╗███████╗███████╗
██╔════╝██╔════╝██╔════╝
███████╗███████╗█████╗  
╚════██║╚════██║██╔══╝  
███████║███████║██║     
╚══════╝╚══════╝╚═╝     
                        
       by HectorH06 (@HectorH06)          version 12.4
```

### General Description

Store Sales Forecasting for a Kaggle competition: https://www.kaggle.com/competitions/store-sales-time-series-forecasting/overview

```diff
- The final model was catboost with a RMSLE of 0.39817
```

Several quarto documents are uploaded, in order they are:
- store_sales_forecasting: SNAIVE (0.52245)
- store_sales_forecasting_レミ1: XGB
- store_sales_forecasting_レミ2: ETS
- store_sales_forecasting_レミ3: ARIMA (0.43872)
- store_sales_forecasting_レミ4: SARIMA (0.43089)
- store_sales_forecasting_レミ5: SARIMA Log

The quarto docs that don't have a score did not really work :/

The only jupyter here is the one that actually got a nice score (LGBM vs CatBoost)
- LGBM: constant 0.40705
- CatBoost: at first 0.39817, then 0.40497 because of a seed update (couldn't get it back)

## Installation

1. Install requirements with the following command :

   `pip install numpy pandas scikit-learn lightgbm catboost matplotlib seaborn`

## References
I used models and feature engineering from these two models

1. https://www.kaggle.com/code/abzu1245/ds24-class9-group1-kume
2. https://www.kaggle.com/code/wajahat1064/store-sales-prediction-blended-model
