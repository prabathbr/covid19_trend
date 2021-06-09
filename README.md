[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
# COVID-19 trend forecasting and visualising with Facebook Prophet

A simple Python script (Jupyter Notebook : COVID19_Trend.ipynb) to forcast COVID-19 daily cases for a given country using Facebook Prophet and "Our World in Data" data source (continuously up-to-date).

## Initial Parameters
Please set initial paramerters as required.

1. Set data source : data_source = 'https://covid.ourworldindata.org/data/owid-covid-data.csv'
1. Select Country : show_country = 'Spain'
1. Adjusting trend flexibility : trend_flexibility = 1.0
1. Set number of forcasting days : days_forcasting = 90
1. Set number of previous days to be considered for forcasting : last_days_count = 30 

## Requirements
1. Facebook Prophet : "install -c conda-forge fbprophet"
1. Plotly : "conda install -c plotly plotly"
1. Pandas : "conda install -c conda-forge pandas"
1. Matplotlib : "conda install -c conda-forge matplotlib"

## Credits
1. "Our World in Data" and its respective authors for providing up-to date data at https://github.com/owid/covid-19-data/tree/master/public/data
1. Facebook, Inc. and its affiliates for "Facebook Prophet" library at https://github.com/facebook/prophet
1. Authors and affiliates of all other libraries and technologies (including Python, Pandas, Plotly and Matplotlib) used in this script.

## References
1. Facebook Prophet : https://facebook.github.io/prophet/docs/quick_start.html#python-api
1. "Our World in Data" Data Source CSV : https://github.com/owid/covid-19-data/blob/master/public/data/owid-covid-data.csv
1. Trend Flexibility : https://facebook.github.io/prophet/docs/trend_changepoints.html#automatic-changepoint-detection-in-prophet
   
## Sponsor
DataDisca Pty Ltd, Melbourne, Australia

[https://www.datadisca.com](https://www.datadisca.com)
