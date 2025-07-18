# AMAZON-PRODUCT-REVIEW-ANALYSIS

## Project Overview

Generating insight that can guide product improvement, marketing strategies and customer engagement.

## Data Source

The Data was shared on Canvas LMS by Digital Skillup Africa (DSA)

## Tools Used

Microsoft Excel
    - For Cleaning
    - For Analysis
    - For Dashboard Creation

    
## Exploratory Data Analysis
EDA involved the exploring of the Data to answer some questions about the data such as;

      1. What is the average discount percentage by product category?

      2. How many products are listed under each category?

      3. What is the total number of reviews per category?

      4. Which products have the highest average rating?

      5. What is the average actual price vs the discounted price by category?

      6. Which product have the highest number of reviews?

      7. How many product have a discount of 50% or more?

      8. What is the distribution of product ratings?

      9. What is the total potential revenue (actual price x Rating count) by category?

      10. What is the number of unique products per price range bucket?

      11. How does the rating relate to the level of discount?

      12. How many products have fewer than 1000 reviews?

      13. Which categories have products with the highest discounts?

      14. Identify the top 5 products in terms of rating and number of reviews combined?


## Data Analysis

Pivot table and chat was used to answer the questions

## Result Finding

      1. What is the average discount percentage by product category?
      

                Product Category	Average of discount_percentage
Home Improvement	58%
Computers & Accessories	54%
Health & Personal Care	53%
Electronics	51%
Musical Instruments	46%
Car & Motorbike	42%
Home & Kitchen	40%
Office Products	12%
Toys & Games	0%
Grand Total	48%
<img width="448" height="342" alt="image" src="https://github.com/user-attachments/assets/ae1cd033-3e2a-442c-9baa-bc384137bad9" />


      2. How many products are listed under each category?

            Product Category	Count of product_name
Car & Motorbike	1
Health & Personal Care	1
Toys & Games	1
Home Improvement	2
Musical Instruments	2
Office Products	31
Home & Kitchen	448
Computers & Accessories	453
Electronics	526
Grand Total	1465
<img width="626" height="342" alt="image" src="https://github.com/user-attachments/assets/0726a02f-a024-48e6-b308-597e22432bda" />



      3. What is the total number of reviews per category?

            Product Category	Count of review_title
Electronics	526
Computers & Accessories	453
Home & Kitchen	448
Office Products	31
Musical Instruments	2
Home Improvement	2
Car & Motorbike	1
Toys & Games	1
Health & Personal Care	1
Grand Total	1465
<img width="677" height="342" alt="image" src="https://github.com/user-attachments/assets/61a7dc14-e512-4b31-9d44-6a7cae83197d" />



      4. Which products have the highest average rating?

            Office Products has the highest rating of 4.3
            Product Category	Average of rating
Office Products	4.3
Grand Total	4.3
<img width="677" height="94" alt="image" src="https://github.com/user-attachments/assets/98405a6d-842e-4ff8-af77-7c6dcecf0697" />



      5. What is the average actual price vs the discounted price by category?

            Product Category	Average of actual_price	Sum of discounted_price
Car & Motorbike	4000.0	2339.0
Computers & Accessories	1683.6	381720.6
Electronics	10127.3	3138057.0
Health & Personal Care	1900.0	899.0
Home & Kitchen	4162.1	1044115.8
Home Improvement	799.0	674.0
Musical Instruments	1347.0	1276.0
Office Products	397.2	9349.0
Toys & Games	150.0	150.0
Grand Total	5445.0	4578580.4
<img width="928" height="342" alt="image" src="https://github.com/user-attachments/assets/b70b311b-4f39-4272-8372-25405b8ffe23" />



      6. Which product have the highest number of reviews?

              Electronics have the highest number of review of 526
              Product Category	Count of review_title
Electronics	526
Grand Total	526
<img width="677" height="94" alt="image" src="https://github.com/user-attachments/assets/19099d2f-6162-41db-83f8-6f2f846c71c5" />


      7. How many product have a discount of 50% or more?

            Product Category	Average of discount_percentage
Computers & Accessories	54%
Electronics	51%
Health & Personal Care	53%
Home Improvement	58%
Grand Total	52%
<img width="677" height="187" alt="image" src="https://github.com/user-attachments/assets/26abbf3d-7076-4e69-ba12-e0e6debee7dc" />



      8. What is the distribution of product ratings?

              rating	Count of review_title
(blank)	1
2-3	6
3-4	348
4-5	1110
Grand Total	1465
<img width="677" height="187" alt="image" src="https://github.com/user-attachments/assets/87d8c6da-50a3-435a-829c-8825457ed034" />



      9. What is the total potential revenue (actual price x Rating count) by category?

              Product Category	Sum of Potential Revenue
Toys & Games	2.38M
Car & Motorbike	4.47M
Home Improvement	6.16M
Health & Personal Care	6.96M
Office Products	60.78M
Musical Instruments	151.12M
Home & Kitchen	10459.72M
Computers & Accessories	12614.81M
Electronics	98020.81M
Grand Total	121327.21M
<img width="677" height="342" alt="image" src="https://github.com/user-attachments/assets/3b2dd55a-eb7f-4d5c-a4d2-3dd10818c81f" />



      10. What is the number of unique products per price range bucket?

                actual_price	Count of product_id
0-10000	1276
10000-20000	91
20000-30000	48
30000-40000	16
40000-50000	13
50000-60000	10
60000-70000	5
70000-80000	4
80000-90000	1
130000-140000	1
Grand Total	1465
<img width="690" height="373" alt="image" src="https://github.com/user-attachments/assets/43cbaa5a-77c5-4e99-9fa0-b8bc958f00fc" />



      11. How does the rating relate to the level of discount?

              rating	Count of discounted_price	Sum of discounted_price
(blank)	1	2099
2-3	6	3108
3-4	348	595482.21
4-5	1110	3977891.22
Grand Total	1465	4578580.43
<img width="979" height="187" alt="image" src="https://github.com/user-attachments/assets/64346b9d-8d93-42ff-8fa5-024933ea74c6" />



      12. How many products have fewer than 1000 reviews?

              Product Category	Count of review_title
Car & Motorbike	1
Computers & Accessories	453
Electronics	526
Health & Personal Care	1
Home & Kitchen	448
Home Improvement	2
Musical Instruments	2
Office Products	31
Toys & Games	1
Grand Total	1465
<img width="677" height="342" alt="image" src="https://github.com/user-attachments/assets/60c38957-1bfe-41a3-9f39-ee8f808c5c48" />



      13. Which categories have products with the highest discounts?

              Electronics have the highest discount of 3138057
              Product Category	Sum of discounted_price
Electronics	3138057
Grand Total	3138057
<img width="677" height="94" alt="image" src="https://github.com/user-attachments/assets/1239ba61-de7c-40ea-80ba-8a4ab1a0dbba" />



      14. Identify the top 5 products in terms of rating and number of reviews combined?

              Product Category	Count of rating	Count of review_title
Electronics	526	526
Computers & Accessories	453	453
Home & Kitchen	447	448
Office Products	31	31
Home Improvement	2	2
Musical Instruments	2	2
Grand Total	1461	1462
<img width="979" height="249" alt="image" src="https://github.com/user-attachments/assets/ca0dc243-d6c1-4ce1-b7f6-0596590af7c6" />



## Dashboard


<img width="2401" height="1396" alt="image" src="https://github.com/user-attachments/assets/c5d5b006-ac6d-474d-bf73-e6824b6ce043" />


