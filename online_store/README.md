# Data: 

The `hypotheses_us` table (hypotheses used for first part of project):

- *Hypotheses* — brief descriptions of the hypotheses
- *Reach* — user reach, on a scale of one to ten
- *Impact* — impact on users, on a scale of one to ten
- *Confidence* — confidence in the hypothesis, on a scale of one to ten
- *Effort* — the resources required to test a hypothesis, on a scale of one to ten. The higher the Effort value, the more resource-intensive the test.


The `orders_us` table (customer orders):

- *transactionId* — order identifier
- *visitorId* — identifier of the user who placed the order
- *date* — of the order
- *revenue* — from the order
- *group* — the A/B test group that the user belongs to


The `visits_us` table (when the customer visited):

- *transactionId* — order identifier
- *visitorId* — identifier of the user who placed the order
- *date* — of the order
- *revenue* — from the order
- *group* — the A/B test group that the user belongs to


# Goal:
Prioritize the given hypotheses, launch an A/B test, and analyze the results

# Content:
- Opening the data file, and preprocessing the data
- Prioritize the hypotheses
- Carry out A/B tests and analyze the results
- Conclusion

# Libraries used
pandas

matplotlib.pyplot

scipy

numpy

seaborn
