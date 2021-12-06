# Amazon Vine vs. Non-vine Ratings Analysis
## Overview of Analysis
The purpose of this analysis is to determine if there is potential for bias in ratings for products that are rated as part of the Amazon Vine program.  This analysis used the Tools category from the reviews datasets provided by Amazon at the location below:

https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Tools_v1_00.tsv.gz

## Results

The following information was found in the data:
- Total number reviews
    - Vine: 268
    - Non-Vine: 29,517
- 5-star Reviews 
    - Vine: 149
    - Non-Vine: 13,675
- Pct reviews that were 5-stars:
    - Vine: 55.6%
    - Non-Vine: 46.3%

## Summary
Given the difference in percentage of 5-star ratings between Vine and non-Vine reviews, it is possible that the reviewers selected as part of the Vine program were biased in favor of the product in some way.  However, more analysis would be needed to confirm if bias does exist due to the much smaller sample size from the Vine program.  

Completing a similar analysis across all product categories is advised to determine if a similar difference in percentage of 5-star ratings between Vine and non-Vine reviews exists for all categories.