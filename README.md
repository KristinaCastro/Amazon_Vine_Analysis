# Amazon_Vine_Analysis
## Overview of the analysis:
We are tasked with analyzing Amazon reviews from the paid Amazon Vine program, where select members of Amazon's reviewer community are compensated to review sample products & also allows manufacturers and publishers to receive reviews for their products. The Amazon Vine program is a service where companies pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. The primary objective of this analysis is to determine if there is any bias toward favorable reviews from the Amazon Vine members compared to non Amazon Vine program members in the available dataset.

## Results 
Below is the extracted Vine table from the dataset:

![Vine_table](https://user-images.githubusercontent.com/81998045/129453305-ec74a4ef-2ff3-4859-b797-98c705eed7bc.png)


From the Vine table, I further filtered to create a vine program review table and a non-vine program review table:

<img src="https://user-images.githubusercontent.com/81998045/129451145-bcddf9da-3c25-4ffd-940b-66608d89c4a3.png" width="480"/> <img src="https://user-images.githubusercontent.com/81998045/129451175-c430850c-afd3-4abc-be95-7e8dd9b363ae.png" width="480"/> 

  1) How many Vine reviews and non-Vine reviews were there?
  
      - As shown below, there are a total of 22 Vine reviews and 26,987 non-Vine reviews 
  2) How many Vine reviews were 5-star? How many non-Vine reviews were 5-star?
  
      - As shown below, there are 13 - 5-star Vine reviews and 14,475 - 5-star non-Vine reviews 
    
<img src="https://user-images.githubusercontent.com/81998045/129456103-82aefed6-ca67-45c6-92f0-f3044653dc67.png" width="480"/> <img src="https://user-images.githubusercontent.com/81998045/129456114-b47d2e89-f366-4ae2-a7fc-7f9c4610f329.png" width="480"/> 

  3) What percentage of Vine reviews were 5-star? What percentage of non-Vine reviews were 5-star?
   
      - As shown below, 59% of Vine reviews were 5-star while 53% of non-Vine reviews were 5-star

<img width="1022" alt="Screen Shot 2021-08-13 at 11 13 46 PM" src="https://user-images.githubusercontent.com/81998045/129456137-df4e4f3b-f8b6-464e-b0ec-e86d2aea50d3.png">

## Summary
Within this dataset, there is a slight positive bias towards paid vine reviews compared to unpaid non-Vine reviews. Even though there were only 22 vine-reviews, 59% of those vine reviews were 5-star reviews. On the other hand, there were a lot more non-Vine reviews, 26,987, and 53% of those non-Vine reviews were 5 star. As a result, paid Vine reviewers tend to give a slightly larger percentage of 5-star reviews then non-Vine reviewers. To further the analysis, I would recommend extending the criteria to 4- or 5-star reviews to get a better sense of the data as a whole. Comparing & grouping the 4- and 5-star reviews would provide more true insight to any bias that may exist.


