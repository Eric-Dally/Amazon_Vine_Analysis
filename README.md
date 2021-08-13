# Amazon_Vine_Analysis

## Overview

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. In this project, I compiled reviews from Amazon’s outdoor products to determine whether Vine members entered more favorable reviews. For the ETL process I used PySpark to extract and transform the data, connected it to an AWS RDS instance, and loaded the transformed data into pgAdmin. Then I used pandas to analyze the reviews. 

## Results

There were 3137 total Vine reviews and a total of 2299255 non-Vine reviews:

<img width="677" alt="Screen Shot 2021-08-13 at 6 04 12 PM" src="https://user-images.githubusercontent.com/82424250/129425831-237ed4f9-a6e9-4781-b290-07487e6cd9cf.png">


