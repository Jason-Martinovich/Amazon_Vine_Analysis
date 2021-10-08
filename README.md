# Amazon_Vine_Analysis

## Overview
This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
We focused on the US reviews for video games.

## Results
### Total number of reviews

~Vine reviews

![vine_review](vine_review.png)
              
              
~Non-Vine reviews

   ![unpaid_vine](unpaid_vine.png)
              
              
### Total number of 5 star reviews
~Vine reviews

   ![5star_vine](5star_vine.png)
              
              
~Non-Vine reviews

   ![5star_nonvine](5star_nonvine.png)
              
              
### Percentage of 5 star reviews
~Vine reviews

   ![percent_vine](percent_vine.png)
              
              
~Non-Vine reviews

   ![percent_nonvine](percent_nonvine.png)
              
              
## Summary
51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the Vine program.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.
