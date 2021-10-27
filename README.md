# SQL-Assignment


# Situation 1- 

Problem – To find out which show the person watched first after buying an OTT’s subscription plan.







Solution – We have used lag to find out what the first entry is on the basis of username for the person after they have bought the subscription.
We created a new variable called 1st_show, we denoted the value of 1 against it, when it was the first entry for a distinct user_id after purchasing the subscription.
Then we recalled our final solution by asking SQL to return, the show column as first show and user_id where the 1st_show variable had the value of 1.
Hence, we get our desired result.
