# Amazon Vine Analysis
Big Machine Learning

# Overview
Some of the reviews left on Amazon are written by members of the paid Amazon Vine program.   This program allows manufacturers and publishers to receive reviews for their products.    The purpose of this analysis is to determine if there is any bias toward favorable reviews from Vine members.   SellBy stakeholders want to understand how this process effects their business.   For the purpose of this analysis, the focus is on the reviews in the tools category.

To begin the analysis the data was first filtered.    The analysis only looked at items with over 20 reviews. 

<img src="/images/over20.png" width="900"> [over20.png]
(/images/over20.png)

The data was then filtered again to include only helpful reviews.    To be determined as helpful, the item's helpful votes divided by total votes had to be equal or greater than 50%.

<img src="/images/helpful.png" width="900"> 
[helpful.png](/images/helpful.png)

The data was then analyzed to review paid vs unpaid reviews.  Below is the summary of the categories:

Unpaid Reviews:

<img src="/images/unpaid_reviews.png" width="600"> [unpaid_reviews.png](/images/unpaid_reviews.png)

Paid Reviews:

<img src="/images/Paid_reviews.png" width="600"> [Paid_reviews.png](/images/Paid_reviews.png)

## Summary Statistics
- Total Reviews:
  - Paid: 285
  - Unpaid: 31,545

- 5 Star reviews:
  - Paid: 163
  - Unpaid: 14,614
  
- Percentage of reviews that were 5 stars:
  - Paid: 57.19%
  - Unpaid: 46.33%


# Summary: 
Overall, there is a positive bias towards reviews that were paid through the Vine program.    In the analysis, there was a  10.86% difference between the positive paid reviews compared to the unpaid reviews.   

The analysis for this category is not truly complete.   To fully understand if this is a bias, the same analysis should be run on all levels of ratings.   Then it could be determined if there is a bias is noted in the one, two, three and four star reviews.    

Another concern is the low amount of paid reviews.   Being only 285 reviews versus 31,545 of non paid reviews is a wide variance.   It is highly recommended that the full analysis be done for several other item categories to ensure the trend continues across product fields.  

With the above information, it can be clear whether an investment in Vine would be appropriate for Sellby.


