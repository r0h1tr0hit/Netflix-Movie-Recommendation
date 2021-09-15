# Netflix-Movie-Recommendation

## Problem Statement

Netflix is a platform which provides movies to its user. It also helps their user by recommending the movie that they might love based on the user's previous watched movie history. Netflix has provided some data of their user. Our job is to use some machine learning model to predict the rating of a movie that the user might give to this movie.

## Performance Metrics

1. RMSE
2. MAPE

## Objective

1. Predicting a rating given by the user to a movie
2. Reduce the RMSE and MAPE error.

## References
<ul>
<li> https://www.netflixprize.com/rules.html</li>
<li> https://www.kaggle.com/netflix-inc/netflix-prize-data</li>
<li> Netflix blog: https://medium.com/netflix-techblog/netflix-recommendations-beyond-the-5-stars-part-1-55838468f429 (very nice blog)</li>
<li>Applied AI course.</li>
  
  
## Models used
### 1. Matrix Factorization Models - SVD, SVDpp
### 2. xgboost model
  
## Results

Models | RMSE | MAPE 
--- | --- | --- 
SVD | 1.0726046873826458 | 35.01953535988152
  --- | --- | --- 
SVDpp | 1.0728491944183447 | 35.03817913919887
  --- | --- | --- 
XGBOOST | 1.0748617789625716 | 34.734311920441556
