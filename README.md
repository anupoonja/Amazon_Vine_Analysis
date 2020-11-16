# Amazon_Vine_Analysis

## Overview of the Analysis:

The purpose of this analysis are mentioned below:
* To perform ETL process using PySpark on one of the 50 datasets.
* To connect to the AWS RDS instance after extracting and transforming the data.
* To load the transformed data into pgAdmin.
* To determine bias toward favotable reviews from Vine members using PySpark, Pandas or SQL.

## Results:

### How many Vine reviews amd non-Vine reviews were there?

Out of the total **14537** helpful reviews, **60** were Vine reviews and **14477** were non-Vine reviews.

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

Out of the total **60** Vine reviews, **34** were 5-star reviews.
Out of the total **14477** non-Vine reviews, **8212** were 5-star reviews.


### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

**56%** of Vine reviews were 5 stars. **56%** of non-Vine reviews were 5 stars.

## Summary:

**56%** of the total Vine reviewers gave 5-star rating. **56%** of the total non-Vine reviews were 5 stars too.

From the above result we can determine that there was no bias by the Vine members in giving 5-star rating.
The 5-star ratings by Vine members are same as non-Vine reviewers.

We can use the **verified_purchase** column to determine the percentage of total Vine reviewers who are verified to have purchased the product.
This will determine if the reviews are genuinely given after buying the product or not.


