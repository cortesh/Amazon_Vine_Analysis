# Amazon_Vine_Analysis

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

## Overview of the analysis: 

The purpose of this analysis is to determine if there is any bias toward favorable reviews from Vine members in your dataset.  Out of 50 possible datasets, I have chosen video games to conduct the study.


## Results: Using bulleted lists and images of DataFrames as support, address the following questions:


* How many Vine reviews and non-Vine reviews were there?

There were 94 Vine reviews and 40,471 non-Vine reviews.

![total count](https://github.com/cortesh/Amazon_Vine_Analysis/blob/main/total_count.jpg)

* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

48 Vine reviews received 5 stars.

![ratings count](https://github.com/cortesh/Amazon_Vine_Analysis/blob/main/group_by_rating.jpg)

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

51% of Vine reviews vs 39% of non-Vine reviews received 5 stars.

![summary table2](https://github.com/cortesh/Amazon_Vine_Analysis/blob/main/final_tbl2.jpg)

## Summary: 

It appears that there is in fact a positivity bias for reviews in the Vine program (12% delta).  The great disparity in sample size leaves room for doubt as to the validity of these findings.  Perhaps a sample t-test with a similar sized non-Vine review would correct for the skew in sample size. 
