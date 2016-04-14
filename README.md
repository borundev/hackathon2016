# Hackathon 2016

**These files are for internal consumption by the group so will not make sense to outsiders**

1. Process_original_data_and_exploration.ipynb file should be run first, atleast the first part as it processes the raw data and converts the time related variables into pandas datetime format for faster loading and processing on subsequesnt runs. The rest of the file explores the data.

2. time_series_by_day.ipynb explores the autocorrelation of the data and then uses the last 15 days values, along with month and weekday to predict. In the second part monthly data on temperature and precipitation is included and seems to give very little benefit. it is very likely that monthly data is not sufficient when much stronger autocorrelation occurs on a week scale (see plot in the file). 
