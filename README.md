# stats19-api
Rest API for serving Stats19 Road Safety Accident Data in GB

## Motivation 

Road safety data about the circumstances of personal injury road accidents in GB available on [data.gov.uk](https://data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-safety-data). This dataset contains the types of vehicles involved in accidents and the consequential casualties. The statistics relate only to personal injury accidents on public roads that are reported to the police, and subsequently recorded, using the STATS19 accident reporting form.

This dataset comes in separate zipped excel or csv files by data table and by year.

Analyst most often interested in the details of accidents with the last 5-10 years of certain location. This requires them to download, unzip, combine multiple files and filter it down for a specific geographic area. A web API serving data in response to carefully constructed http requests is a modern way to provide data for users and simplify the proccess. An API will also allow the analysist to build their own static or dynamic applications.

## User guide
- Todo

## Libraries used
- SQLalchemy
- Flask

## Summary of the results of the analysis
- Todo

## Acknowledgements
The road traffic accident data is governed by [Open Government Licence](http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)
    http://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/
    
The Flask API is governed by [MIT License](https://github.com/GaborJenei/stats19-api/blob/26d6b57df8639e8677eec194b72cd7223ba37789/LICENSE)
