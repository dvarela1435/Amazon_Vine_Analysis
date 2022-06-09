# Amazon_Vine_Analysis

## Overview of the analysis: 

Analyze Amazon reviews written by members of the paid Amazon Vine program. SellBy paid a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

## Results: 

The dataset used is Amazon Reviews for US Pet Products, taken from https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Pet_Products_v1_00.tsv.gz

### Total Vine reviews and non-Vine reviews

- 2,643,619 reviews were populated into the database that came from the dataset provided by Amazon
- of those, 39,376 reviews had a total of votes were greater or equal to 20
- of those, 38,010 had helpful votes equal to or greater than 50% 

![screen_1](/resource/total_overall_counts.png)

Out of the 38,010 reviews
- 170 were vine reviews
- 37,840 were non-vine reviews

![screen_2](/resource/total_vine_reviews.png)

### Vine reviews and non-Vine reviews were 5 stars

- 65 Vine reviews that were rated 5 stars
- 20,612 non-Vine reviews that were rated 5 stars

![screen_3](/resource/five_star_review.png)

### Percentage of Vine reviews and non-Vine reviews were 5 stars

- 38.2% of the Vine reviews were 5-star reviews
- 54.5% of the non-Vine reviews were 5-star reviews

![screen_4](/resource/per_five_star_review.png)


## Summary: 

With this dataset, there doesn't seem to be a positivity bias for reviews in the Vine program. Only a third of the reviews were rated 5-star. This doesn't necessarily mean that only 5-stars reviews are positive. This could be expanded to include reviews that are 4-star reviews. If 4-stars were included in this review, then it could increase the percentage of 38.2% to a higher amount. 
