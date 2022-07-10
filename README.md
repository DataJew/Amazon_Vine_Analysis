# Amazon Vine Analysis

## Overview of Project
Since your work with Jennifer on the SellBy project was so successful, you’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

This new assignment consists of two technical analysis deliverables and a written report.

1. ***Deliverable 1:*** Perform ETL on Amazon Product Reviews
2. ***Deliverable 2:*** Determine Bias of Vine Reviews
3. ***Deliverable 3:*** A Written Report on the Analysis [`README.md`](https://github.com/DataJew/Amazon_Vine_Analysis)

## Results

***How many Vine reviews and non-Vine reviews were there?***


![R1](https://github.com/DataJew/Amazon_Vine_Analysis/blob/main/Resources/images/R1.png)


***How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?***

***What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?***


![R2.3](https://github.com/DataJew/Amazon_Vine_Analysis/blob/main/Resources/images/R2.3.png)



## Summary

* Of all the reviews for Furniture products *(792,133)*, only **0.4%** *(2,775)* are from Vine particpants.
* Of all the 5-star reviews *(447,716)*, **0.3%** *(1356)* are from Vine particpants, with **99.7% (446,360)** from non-Vine particpants



### ADDITIONAL ANALYSIS

A new dataset exclusivly for Vine products can provide a more meaningful breakdown of ratings to support the positive bias for reviews in the Vine program.


![R4](https://github.com/DataJew/Amazon_Vine_Analysis/blob/main/Resources/images/R4.png)
