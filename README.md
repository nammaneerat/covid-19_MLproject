## Analysis of the COVID-19 spreading rate and the 7-day forecasting model in the US

#### (Patcharaporn Maneerat,Yuexin Li, Danqing Wang)

The coronavirus 2019 (COVID-19) has been severely spreading across the US, and the state governors
and federal government have issued several orders to control the situation. According to this circumstance
this study aims to (1) find factors influencing the virus spreading rates across the country, and (2) predict
the confirmed and dead cases in the US and NY with their historical trend. To answer the first question,
we defined two measurements for the spreading rates and employed a random forest model to examine
the features influencing the rates. We found that population, population density and degree of
urbanization are the most important factors affecting the spreading rates. For the second question, we
selected the features considering p-value, R-squared and RMSE, and applied the linear and polynomial
regression to predict the confirmed and dead cases in the next 7 days using the historical time series from
Jan 22 - May 7, 2020. We observe that not all state or federal orders are good features for the forecasting
models. Also, the confirmed and dead forecasting models are performed better after raising the
polynomial degree. However, for our final models, we decide to keep the degree low while the R-squared
and RMSE are still significantly improved from the original linear models. Accordingly, this project is the
preliminary work that will improve our understanding of the virus spreading factors and be useful for
further studies.
