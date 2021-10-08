# Amazon_Vine_Analysis

## Overview
This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members.
The analysis uses PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin and calculate different metrics.
We focused on the US reviews for video games.

## Results
### Total number of reviews

~Vine reviews

   ![vine review](vine review.png)
              
              
~Non-Vine reviews

   ![unpaid vine](unpaid vine.png)
              
              
### Total number of 5 star reviews
~Vine reviews

   ![5star vine](5star vine.png)
              
              
~Non-Vine reviews

   ![5star non vine](5star non vine.png)
              
              
### Percentage of 5 star reviews
~Vine reviews

   ![percent vine](percent vine.png)
              
              
~Non-Vine reviews

   ![percent non vine](percent non vine.png)
              
              
## Summary
51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the Vine program.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.
