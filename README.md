# Amazon Vine Analysis

## Overview of Project
Since your work with Jennifer on the SellBy project was so successful, you’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

## Deliverables:
This new assignment consists of two technical analysis deliverables and a written report.

1. ***Deliverable 1:*** Perform ETL on Amazon Product Reviews
2. ***Deliverable 2:*** Determine Bias of Vine Reviews
3. ***Deliverable 3:*** A Written Report on the Analysis [README.md](https://github.com/DataJew/Amazon_Vine_Analysis)

### RESULTS

# ***How many Vine reviews and non-Vine reviews were there?

* 
* ![R1](https://github.com/DataJew/Amazon_Vine_Analysis/blob/main/Resources/images/R1.png)


# ***How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
# ***What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

* 
* ![R2.3](https://github.com/DataJew/Amazon_Vine_Analysis/blob/main/Resources/images/R2.3.png)


### SUMMARY


1. The majority of reviews for Furniture product are almost nothing or lower results from Vine participants: **99.6% are Non-Vine**.  
2. And overall of all 5 Star reviews are also the same as the Furniture, all are from Vine participants: **99.7% of all 5-star reviews are non-Vine**.
3. But we need to highlight that not all of the 5 Star reviews are coming from Vine participants.

## ADDITIONAL ANALYSIS

4. Due to these results, creating a dataset that focuses soley on Vine products may provide meaningful insight(s).

![R4](https://github.com/DataJew/Amazon_Vine_Analysis/blob/main/Resources/images/R4.png)
