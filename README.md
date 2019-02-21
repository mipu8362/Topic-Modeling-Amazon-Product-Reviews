## Topic-Modeling-Amazon-Product-Reviews
This repo is an example of using k-Means Topic Modeling in Python to deliver marketing and product insights for the popular clothing/shoes brand, Puma. Specifically, I leverage two datasets: (1) meta-data about products and (2) product reviews. The aforementioned database has reviews on all types of Amazon products, but these datasets are huge (~80gb). They can be accessed via the link at the top of this repository.

  Puma is the third-largest sportwear manufacturer in the world and has been around for over seventy years, so it was easy to assume there was extensive information about their products on Amazon. Using Amazon’s meta product data in conjunction with the reviews dataset, I was able to identify the ASINs associated with this brand and leverage the meta data to only contain Puma products. Next, with that list of ASINs, I extracted the 27,149 reviews Amazon users had written about Puma products from the second dataset and processed those into a text file for analyzation. Needless to say, this produced an overwhelming about of data. So, it only made sense to further process and potentially segment this data to get the most insights. 

  I wanted to find out what consumers liked and did not like about Puma products. When were they buying these products? For who? And, at what price? For this reason, I chose to segment the data by ‘stars’ and focus on the highest-rated and lowest-rated reviews. This was completed easily by separating the data with a for loop and performing topic models on two critical score ranges: low-star ratings (1 or less) and ratings that are positive (4-5). From a marketing standpoint, it is important to look at reviews that are critical. With this information, I felt I could produce the best reflection of what Puma consumers are enjoying about their products (from the 4-5 star category) and what they were not (within the 1 star or less category). 


### File Description:
####  1. 1_Star_Printed_Topics.txt
  
    Topic Model of worst reviews.
####  2. 4_Star_Printed_Topics.txt
  
    Topic Model of best reviews.
####  3. Topic Modeling Amazon Product Review - Puma.docx
  
    Final written report, data analysis, and brand insights.
####  4. Topic Modeling Amazon Review Data.ipynb
  
    Python project script.
####  5. allpumareviews.json
  
    All Puma reviews on Amazon.
