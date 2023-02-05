# Amazon_Vine_Analysis
## Overview
Conducting a meta-analysis of Amazon evaluations was the main goal of this effort. It developed specifically to examine evaluations written as part of the Amazon Vine program, where a select group of Amazon reviewers are paid to review sample goods. The main objective of this investigation is to ascertain whether the available data is biased in favor of positive evaluations from the compensated Vine members.

I selected to analyze evaluations in the Pet category, which requires expertise and knowledge to review successfully, out of the 50 datasets of product categories accessible. As instructed, the project's initial ETL phase was carried out utilizing AWS, Postgresql, and PySpark in Google Colab. Google Colab and PySpark were used for the data analysis section. 
Data Source: 
Data Tools: Google Colab, Pyspark, AWS, PostgreSQL


## Results

## Vine Reviews vs. Non-Vine Reviews

**Number of Vine Reviews**

|  count|                90|

**Number of Non-Vine Reviews**

|  count|            37,385|

For video game reviews there were 90 Vine reviews and 37,385 Non-Vine reviews.

## How Many and Percentage 5 Star Reviews

**Vine Review Breakdown**

![Vine_5Star](https://user-images.githubusercontent.com/92001105/154822774-ad19b92f-cae5-452c-8437-90804374ade1.png)

**Non-Vine Review Breakdown**

![Non_Vine_5Star](https://user-images.githubusercontent.com/92001105/154822781-526f8abd-5a65-4646-af52-1319ae8726e6.png)

For Vine Reviews there were 44 of 90 reviews that were rated 5 stars or 49% of total. For Non-Vine Reviews there were 14,626 5 star reviews of 37,385 total reviews or 39% of total.

## Summary
There were only 90 Vine reviews in total, so the sample size is fairly tiny, but there does seem to be some favorable bias for reviews in the Vine program as 49% of them received a rating of 5 stars as opposed to 39% of non-Vine reviews. Additional analyses might be performed, such as looking at review datasets with more information, particularly for Vine reviews, in order to validate or deny the existence of a favorable bias with Vine reviews. To compare the two groups and establish whether there is a statistically significant difference between them, an extra technique called a paired t-test might be employed.I was unable to access my Amazon RDS due to account being unaccess but was still able to comeplete the project.


