# Amazon_Vine_Analysis

## Overview

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. In this project, I compiled reviews from Amazon’s outdoor products to determine whether Vine members entered more favorable reviews. For the ETL process I used PySpark to extract and transform the data, connected it to an AWS RDS instance, and loaded the transformed data into pgAdmin. Then I used pandas to analyze the reviews. 

## Results

Before doing any analysis, I filtered out all the reviews that did not get at least 20 votes. 


<img width="903" alt="Screen Shot 2021-08-13 at 6 15 54 PM" src="https://user-images.githubusercontent.com/82424250/129426369-e39e3376-6cc6-4628-80c3-e16e0a1bac24.png">


<img width="712" alt="Screen Shot 2021-08-13 at 6 13 27 PM" src="https://user-images.githubusercontent.com/82424250/129426317-eb0ab560-1782-4040-b5f5-46f13db76755.png">



## Summary

Overall, Vine reviews showed a bias. Out of all of the 5 star reviews, Vine reviews accounted for 89% of them while non-Vine reviews accounted for the remaining 11 percent. This suggests that people who purchase the product are more likely to rate a purchase more favorably than one who has not purchased the product.  

