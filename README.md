# Amazon_Vine_Analysis

## Overview of the analysis
The main purpose of this project was to understand and analyze how Amazon Vine Service is successful for the outdoor products that we used. Our raw data contains produinformationons, but mostly reviinformationons such as paid reviews under Vine service or not, the number of total reviews, customer reviews, and if they are valid or not.
As a result, we analyzed the performance of paid Vine products. Steps
- Creating New Database with Amazon RDS
- Creating New Database in pgAdmin to keep the chaUse
- Using Collab and PySpark Extract, Transform and Load the clean data

After th,ese steps we used one of the charts that we created (vinto order to measure to performance of Vine Services
## Results
- How many Vine reviews and non-Vine reviews were there?

Vine Reviews 🔽

![image](https://user-images.githubusercontent.com/98247252/175351567-3c4a0170-ed74-4bd4-9674-9243548215a7.png)

None-Vine Reviews 🔽

![image](https://user-images.githubusercontent.com/98247252/175351873-d96c3f9a-ede5-46fa-8688-c634401d96bb.png)

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

5 stars Vine reviews 🔽

![image](https://user-images.githubusercontent.com/98247252/175352152-652c11ae-fd07-4f61-a016-6563661359bd.png)

5 stars None-Vine reviews 🔽

![image](https://user-images.githubusercontent.com/98247252/175352632-1a7334c1-756e-453e-b72e-072ef1d50d80.png)

Percentage of non-Vine reviews 🔽

![image](https://user-images.githubusercontent.com/98247252/175352938-fdc2a7c7-f2a8-4e55-8ab4-a06a85a206a0.png)

Percentage of Vine reviews 🔽

![image](https://user-images.githubusercontent.com/98247252/175353827-0b594da7-1d84-4058-ac8a-2aad18f98175.png)

## Summary

5 Stars review rates between paid and non-paid reviews are almost identical. Therefore we cannot say that there is positivity bias for in this particular outdoor product.
However outdoor products customer's behaviour can be different than other products. It is always better to do same analysis with other products data. \
According the our dataset, number of paid reviews are 107 and non-paid reviews are 39869. This is a huge difference. In order to support our result, we might want to increase the number of vine customer reviews. 



























