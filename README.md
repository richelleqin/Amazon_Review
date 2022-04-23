# Amazon_Review
## Overview
###
The purpose of this analysis is to choose one of the amazon datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then we will determine if there is any bias toward favorable reviews from Vine members in the chosen dataset.
## Results
- In the kitchen dataset, there were 1,207 Vine reviews and 97,839 non-Vine reviews.
- There were 509 5 stars Vine Reviews and 45,858 non-Vine 5 stars reviews.
- 42.2% of Vine reviews were 5 stars and 46.9% of non-Vine reviews were 5 stars.
## Summary
Based on the percentage of 5 stars reviews, there were no positivity bias for reviews in the Vine program for Kitchen products. This is because in both cases around half the reviews were 5 stars. Further analysis would be to see the proportions of 1 star, 2 star, 3 star, 4 star, and 5 star reviews for Vine and non-Vine. This would enable us to see if there is a skew to the lower ratings for non-Vine reviews as currently we are only checking 5 stars. Further we could also group these ratings by product id, so that we can see if there is a specific product that receive the high ratings was due to Vine.
