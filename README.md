# Bigquery_test
Assignment 1
SELECT* FROM `bigquery-public-data.covid19_open_data.covid19_open_data` 
where country_name = 'India'
and cumulative_deceased > 0
limit 10
