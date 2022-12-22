# Amazon_Vine_Analysis
Using PySpark to analyze the vine reviews 

## Overview 
This project aims to analyze the Amazon Reviews form of Vine to understand if there is any bias. 
To proceed with the project, we used Pyspark to Perform ETL on Amazon Wireless Product Reviews 
to extract the review data.

## Resources
- Data: https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt
- Source: PySpark, Google Colab, ETL, SQL.

## Results 
- How many Vine reviews and non-Vine reviews were there?

![vine1](vine1.png).


- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

![vine2](vine2.png).
![vine3](vine3.png).


- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

![vine4](vine4.png).
![vine5](vine5.png).


## Summary 
After analyzing all the data, it is possible to observe a small higher percentage of the 5 star 
reviews for the Non-Vine program of 25% and 23% for Vine reviews, which do not have a relevant bias.
