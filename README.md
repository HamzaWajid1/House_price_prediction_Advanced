# House Price Prediction with Stacked Regressor 🏡💰

## Abstract 📊
In our quest to predict house prices, we embarked on a journey with a Stacked Regressor model. The validation dataset bowed to our prowess, revealing a minimum root mean square error of 0.3769. This magical model, born from the fusion of Random Forest, Support Vector Regressor, K-Nearest Neighbour Regressor, and Ridge Regressor, outshone its individual counterparts, paving the way for superior predictions.

## Introduction 🚀
Predicting house prices isn't just about numbers; it's a glimpse into the future of the economy. Our nine models, guided by the Kaggle dataset, aimed to unravel the secrets hidden in housing data. As we delved into the business cycle, our mission became clear – understanding the intricate dance of demand and supply in the housing market.

## Dataset 📈
Our journey began with the Kaggle dataset, where "train.csv" held the training data for 1460 houses, and "test.csv" contained data for 1461 houses. A treasure trove of 79 attributes awaited us, each holding a key to unraveling the mystery of house prices.

## Feature Engineering 🔍
With our trusty Jupyter notebook and a sprinkle of Python magic, we set out to pre-process the data. Outliers were vanquished, skewed sales underwent log transformation, and missing values were treated with care. New columns were crafted, and categorical features transformed into numerical wonders. Our dataset was a canvas, and feature engineering was our brushstroke.

## Data Modelling 🤖
A grand ensemble of nine models entered the stage, each showcasing its prowess. Linear Regression, Ridge, Lasso, K-Nearest Neighbour, Decision Tree, Random Forest, Support Vector Regressor, Gradient Boosting Regressor, and the mighty Stacked Regressor – all vying for the crown. The battlefield was marked by root mean square error and k-fold cross-validation, revealing the strengths and weaknesses of each contender.

### Model Performance Summary
- **Linear Regression:** RMSE - 0.4279, Mean CV Score - 0.4752
- **Ridge:** RMSE - 0.3958, Mean CV Score - 0.4167
- **Lasso:** RMSE - 0.4059, Mean CV Score - 0.4298
- **K-Nearest Neighbour:** RMSE - 0.4135
- **Decision Tree:** RMSE - 0.4584, Mean CV Score - 0.4583
- **Random Forest:** RMSE - 0.3862, Mean CV Score - 0.4038
- **Support Vector Regressor:** RMSE - 0.3900, Mean CV Score - 0.4096
- **Gradient Boosting Regressor:** RMSE - 0.4118, Mean CV Score - 0.4292
- **Stacked Regressor:** RMSE - 0.3770, Mean CV Score - 0.4094

The Stacked Regressor emerged victorious, boasting the lowest root mean square error. Scatter plots attested to its unparalleled performance, outshining all other estimators in its realm.

Embark on this journey with us as we unravel the secrets of house price prediction! 🏡✨
