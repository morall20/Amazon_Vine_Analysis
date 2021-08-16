# Amazon_Vine_Analysis
 
 ## Resources

 AWS, postgresql, PySpark, Google Colab, VS Code
 Data: amazon_reviews_us_Video_DVD_v1_00.tsv.gz

 ## Objective

 I’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, I needed to pick a dataset and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset.


## Overview
### Vine Analysis of Amazon Reviews of US Video DVD

Imported the Dataset

![Slide 1](https://user-images.githubusercontent.com/82338072/129496789-9758d6fc-51ec-4ed7-9b48-2007c69f84cb.PNG)

Turn into a Data frame 

![slide2](https://user-images.githubusercontent.com/82338072/129496795-2e4d85c8-8573-4865-b184-dca14c21ef59.PNG)

filter data frame by votes and reviews

![slide3](https://user-images.githubusercontent.com/82338072/129496798-e5c00612-be02-463b-974c-96a3ab335d83.PNG)

talley the totals

![slide 4](https://user-images.githubusercontent.com/82338072/129496806-c4137caa-d695-4920-9d3a-766f432c75dd.PNG)

![Slide5](https://user-images.githubusercontent.com/82338072/129496808-888dcc29-fba4-42c2-bf50-86ca0ea6d24a.PNG)


