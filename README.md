# Amazon_Vine_Analysis
# Overview of the analysis:

In this project, we have access to approximately 50 datasets where each one contains reviews of a specific product, from clothing apparel to wireless products. And we have to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into PgAdmin.After we use PySpark to determine if there is any bias toward favorable reviews from vine members in the dataset.  

# Results:
- Vine reviews are 613 and non-vine reviews are 64968.

![first image](/Resources/image1.PNG
   )
   
 ![first image](/Resources/image2.PNG
   )  
   
 - 5-stars vine reviews are 222 and 5-stars non vine reviews are 30543.

  ![first image](/Resources/image3.PNG
   )
   
   ![first image](/Resources/image4.PNG
   )
   
   - 36.22 percentage of vine reviews are 5-stars and 47.01 percentage of non-vine reviews.
     
   ![first image](/Resources/image5.PNG
   )
   
   ![first image](/Resources/image6.PNG
   )
   
 # Summary: 
 
 The finding of this analysis is 36.22% of vine reviews are 5 stars whereas 47.01% of non-vine reviews. So, it does not appear to be any positivity bias. 
 We could use statistical distribution of the star rating of the vine and non vine reviews.
