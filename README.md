[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
# COVID-19 country-wise trend forcasting with Facebook Prophet

A simple Python script (Jupyter Notebook) to forcast COVID-19 daily cases using Facebook Prophet.

# Inital Parameters
Please set initial paramerters as required.

Set data source : data_source = 'https://covid.ourworldindata.org/data/owid-covid-data.csv'
Select Country : show_country = 'Spain'
Adjusting trend flexibility : trend_flexibility = 1.0
Set number of forcasting days : days_forcasting = 90

# Requirements
Facebook Prophet : "install -c conda-forge fbprophet"
Plotly : "conda install -c plotly plotly"
Pandas : "conda install -c conda-forge pandas"
Matplotlib : "conda install -c conda-forge matplotlib"


## References
Facebook Prophet : https://facebook.github.io/prophet/docs/quick_start.html#python-api
Data Source : https://github.com/owid/covid-19-data/blob/master/public/data/owid-covid-data.csv
Trend Flexibility : https://facebook.github.io/prophet/docs/trend_changepoints.html#automatic-changepoint-detection-in-prophet
   
## Sponsor
DataDisca Pty Ltd, Melbourne, Australia

[https://www.datadisca.com](https://www.datadisca.com)