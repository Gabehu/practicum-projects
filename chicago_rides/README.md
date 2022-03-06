# Data: 
The data is extracted from SQL queries, conducted outside of this notebook file.

The `project_sql_result_01` table (data on taxis):

- *company_name* — taxi company name
- *trips_amount* — number of rides for each taxi company on November 15-16, 2017


The `project_sql_result_04` table (data on dropoff locations and number of rides):

- *dropoff_location_name* — Chicago neighborhoods where rides ended
- *average_trips* — The average number of rides that ended in each neighborhood in November 2017


The `project_sql_result_07` table (rides from the Loop to O'Hare International Airport):

- *start_ts* — pickup date and time
- *weather_conditions* — weather conditions at the moment the ride started
- *duration_seconds* — ride duration in seconds


# Goal:
Find patterns in the available information. Working with a database, analyze data from competitors and test a hypothesis about the impact of weather on ride frequency.

# Content:
- Opening the data file
- EDA
- Perform hypotheses testing
- Conclusion

# Libraries used
pandas

matplotlib.pyplot

scipy

numpy
