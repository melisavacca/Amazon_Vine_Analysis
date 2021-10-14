# Amazon_Vine_Analysis

## Deliverable 1
### The extracted dataset is transformed into four DataFrames with the correct columns and all four are loaded into their respective tables in pnAdmin.  

See images below:

Vine_Table

![image](https://user-images.githubusercontent.com/64279232/137063521-6d76571d-2b7f-4bbe-aa01-bcfd8235700d.png)


Customers_Table

![image](https://user-images.githubusercontent.com/64279232/137063585-cd5728f9-d87c-4f05-b0fb-bf481c42b5b1.png)


Products_Table

![image](https://user-images.githubusercontent.com/64279232/137063666-66ce9acf-ff10-47d7-98dd-1f5042a282c5.png)


Review_ID Table

![image](https://user-images.githubusercontent.com/64279232/137063760-408699d6-e549-4c2a-8aa9-1d5a8c7496fd.png)


## Overview of Project

This project was focused on analyzing Amazon reviews for musical instruments written by members of the paid Amazon Vine program.  The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products.  Companies pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.  I used PySpark to perform the ETL process to extract the musical instruments dataset, transform teh data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.  I was then able to determine if there was any bias toward favorable reviews from Vine members in the musical instrument dataset.  

## Results

- How many Vine reviews and non-Vine reviews were there?
  
  There were 963 Vine reviews and 330,093 non-Vine reviews.  
  

- How many Vine reviews were 5 stars?  How many non-Vine reviews were 5 stars?

  There were 520 5-star Vine reviews and 200,616 5-star non-Vine revies. 
  

- What percentage of Vine reviews were 5 stars?  What percentage of non-Vine reviews were 5 stars?

  54% of Vine reviews were 5 stars and 60.8% of non-Vine reviews were 5 stars. 
  


## Summary 

Although there are many more non-Vine reviews compared to Vine reviews, there does not appear to be positivity bias for the reviews in the Vine program present.  60.8% of the non-Vine reviews were 5 stars, and only 54% of the Vine reviews were 5 stars, making it surprisingly lower.  I think it would be helpful to do further analysis on the helpful votes and total votes for vine compared to non-vine as well.  I also think it would be interesting to gather data on 1 star reviews for both Vine and non-Vine reviews as well.  

