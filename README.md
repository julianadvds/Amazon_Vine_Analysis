# Amazon_Vine_Analysis
## Overview
The Amazone Vine program is a service that allows manufacturers and publishers to receive reviews for their product.  An analysis was done on a set of reviews for items in the "Outdoors" category to determine if there is a bias between the paid and unpaid reviews.
The analysis used the reviews, found at https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Outdoors_v1_00.tsv.gz.  The reviews were then cleaned up and put into 4 different tables for analysis.
Once the data was cleaned and put into a structured database, various metrics were calculated to determine if there is bias between the paid and unpaid reviews.

## Results
The analysis on the outdoor reviews to look at total reviews, number of five star reviews and the percentage of five star reviews between paid and unpaid.

### Number of Reviews
* Paid: 107
* Unpaid: 39,869

### Number of Five Star Reviews
* Paid: 56
* Unpaid: 21,005

### Percentage of Five Star Reviews
* Paid: 52.34
* Unpaid: 52.69


## Summary
From the data analysis, although there are significantly more unpaid reviews compared to paid reviews, it is clear that there is not a bias between the paid and unpaid reviews from the Amazon vine program.  In fact, the percentage of five star reviews was lower for the paid reviews compared to the unpaid results at 52.34% compared with 52.69% for the unpaid.  

To further explore the data, performing some statistical analysis on the data to determine if the sample size of the paid reviews was large enough.  The mean, median and mode and t-tests could be performed to determine if there was a statistical difference between the unpaid and paid reviews which might indicate favourability.



