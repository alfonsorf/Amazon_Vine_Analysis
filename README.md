# Amazon Vine Analysis

## Overview
The purpose of this week's challenge was to use my knowledge of Big Data to create an Amazon Web Services (AWS) database and connect it with PostgreSQL to then analyze the Amazon  Vine customer reviews. Amazon Vine is a program that allows manufacturers and publishers to receive reviews for their products. Along with this analysis I was tasked with creating an Extract, Transform, and Load pipeline for the raw data to ensure correct results.

## Results
After the data transformation and analysis, the results for the Vine reviews are:
- Total Vine reviews:	255
- Vine reviews with 5 star rating: 120
- % of Vine reviews with 5 stars: 47.1%

The results for the non-Vine reviews are:
- Total Non-Vine reviews:	36400
- Non-Vine reviews with 5 star rating: 17167
- % of Non-Vine reviews with 5 stars: 47.2%

## Summary
After completing the Vine vs. Non-Vine review analysis, it does not appear to show any positive bias based on the percentage of 5 star reviews being basically the same for both paid vs unpaid reviews.

Additionally, another analysis that could be done with this data is to compare the 1 star review percentages, as this would be another way to check for bias. In this case it would be a negative bias that could be determined.
