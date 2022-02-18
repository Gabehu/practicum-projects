# Data: 

The `ab_project_marketing_events_us` table (the calendar of marketing events for 2020):

- *name* — the name of the marketing event
- *regions* — regions where the ad campaign will be held
- *start_dt* — campaign start date
- *finish_dt* — campaign end date


The `final_ab_new_users_upd_us` table (all users who signed up in the online store from December 7 to 21, 2020):

- *user_id*
- *first_date* — sign-up date
- *region*
- *device* — device used to sign up


The `final_ab_new_upd_us` table (all events of the new users within the period from  December 7 through January 1, 2021):

- *user_id*
- *event_dt* — event date and time
- *event_name* — event type name
- *details* — additional data on the event (for instance, the order total in USD for purchase events)

The `final_ab_participants` table (table containing test participants):

- *user_id*
- *ab_test* — test name
- *group* — the test group the user belonged to

# Goal:
Carry out EDA and evaluate the A/B test results regarding the new recommender system 

# Libraries used
pandas

matplotlib.pyplot

scipy

plotly

math

seaborn
