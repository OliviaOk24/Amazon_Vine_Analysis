# Amazon_Vine_Analysis

Project Overview 
This project was aimed at analyzing Amazon reviews written by members of the paid Amazon Vine program. The Vine program is a service that allows manufacturers and publishers to receive reviews for their products. For this analysis, I chose the furniture dataset listed on the amazon page. With the use of AWS RDS instance, PySpark, Pandas and SQL, I performed analysis on the furniture reviews dataset. 


Results 

![image](https://user-images.githubusercontent.com/85662949/136726261-81ddb0fc-7b2a-4fd0-b338-006150a32361.png)
![image](https://user-images.githubusercontent.com/85662949/136726283-bfeb0b10-250c-42a2-a4bb-93034af1095d.png)

The images above show the analysis performed to get the information from the given dataset. 

- There were 136 vine reviews(paid)
- There were  18019 non-vine reviews(unpaid)
- Of the Vine reviews, 74 were 5 stars (74 out of 136)
- Of the Non-Vine reviews, 8482 were 5 stars (8482 out of 18019) 
- 54% of Vine Reviews were 5 stars 
- 47%of Non-Vine Reviews were 5 stars 


Summary

From the data provided, I do not suspect there is any positivity bias that greatly affects the vine program. The percentage of 5 star reviews from non vine users is 47% which is not too far off from the 54% of the vine program reviews. If the percentage of the vine 5 star reviews were much higher, I could argue that there was indeed some positivity bias in the program. 

An additoinal analysis that could help support my statement would be to perform some analysis based on the verified purchase column, to make sure that the vine reviews are verified purchases. 
