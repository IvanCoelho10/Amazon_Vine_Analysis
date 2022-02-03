# Amazon_Vine_Analysis Project

## Overview of the analysis: Explain the purpose of this analysis.

The purpose of this analysis is to demonstrate ETL process by extracting, transforming, connecting to AWS RDS instance, and loading transformed data into pgAdmim (postgreSQL). Analysis is then followed by identifying if there is existing bias toward favorable reviews from Vine members in the dataset.
Pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.

## Results

### All four DataFrames are loaded into their respective tables in pgAdmin

#### Products Table

![products_table](https://user-images.githubusercontent.com/87731897/146703282-e062d927-ed50-4994-bcaa-b565275dc2b9.png)

#### Customers table

![customers_table](https://user-images.githubusercontent.com/87731897/146703311-4effc5ff-225c-412b-93f6-8347aa63bd7e.png)

#### Review Id Table

![review_id_table](https://user-images.githubusercontent.com/87731897/146703350-2ceb9b74-9080-448d-842b-894aa2e4cd14.png)

#### Vine Table

![vine_table](https://user-images.githubusercontent.com/87731897/146703380-b854b498-29b8-48f2-bd34-6b56037bf8e6.png)

#### PgAdmin

![pgAdmin](https://user-images.githubusercontent.com/87731897/146703556-1c21eda4-7951-47a9-8c0d-533c08dd44f1.png)

### How many Vine reviews and non-Vine reviews were there?

Total Number of Reviews: 26987

### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

Number of Five Stars of Vine reviews: 0
Number of Five Stars of non-Vine reviews: 14475

### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

Percentage of 5 star review for vine (paid): 0.00000
Percentage of 5 star review for non-vine (unpaid): 0.53637

![Step-5](https://user-images.githubusercontent.com/87731897/146703196-04531564-88c4-4c95-9f48-9278068fe5d1.png)

## Summary

No positivity bias for reviews in the Vine program. In the analysis, there is no evident showing there is any bias toward 5 star reviews from Vine members.
