# A/B-Testing-E-commerce-Marketing-Strategy

# Project Overview
For this project, I delve into the essence of A/B Testing for an E-commerce marketing campaign to choose the best one for future marketing campaigns. My analysis delves deep, comparing the two marketing strategies carried out. Furthermore, I explored the effectiveness of diverse marketing campaigns to make data-driven decisions.

# Importing Essential Python Libraries and Datasets
In this section, I imported vital Python libraries (Pandas, matplotlib, seaborn, DateTime) and the Control Campaign and Test Campaign dataset that serve as the bedrock of my A/B Testing. This initial groundwork is crucial as it sets the stage for the insightful exploration that lies ahead.

# Data Preprocessing and Exploration
In order to comprehend the dataset I’m handling, I engage in data preprocessing and exploration of the dataset. This includes;
1. Changing the column name due to some error in the loaded column names
2. Check for nulled value in the campaign dataset (Control Campaign dataset and Test Campaign dataset)
3. Filling the missing data in the control_data dataset with the median of the column
4. Marge the Control and Test Campaign dataset
5. Count for the occurrences of each unique value in the two dataset using the column 'Campaign Name'

# A/B Testing to Find the Best Marketing Strategy

In this section, I carried out the following A/B testing;
1. Analysis of the relationship between the number of impressions gotten from both campaigns and the amount spent on both campaigns.
2. Analysis of the number of searches performed on the website from both campaigns.
3. Analysis of the number of website clicks from both campaigns.
4. Analysis of the amount of content viewed after reaching the website from both campaigns.
5. Analysis of the number of products added to the cart from both campaigns.
7. Analysis of the amount spent on both campaigns.
8. Analysis of the purchases made by both campaigns.

   Then, I proceeded to analyze some metrics to find which ad campaign converts more by:

1. Analyzing the relationship between the number of website clicks and content viewed from both campaigns.
2. Analyzing the relationship between the amount of content viewed and the number of products added to the cart from both campaigns.
3. Analyzing the relationship between the number of products added to the cart and the number of sales from both campaigns

# A/B Result

From the A/B tests, I found that;

1. The control campaign resulted in more sales and engagement from the visitors.
2. More products were viewed from the control campaign, resulting in more products in the cart and more sales. However, the conversation rate of products in the cart is higher in the test campaign.
3. The test campaign resulted in more sales according to the products viewed and added to the cart. And the control campaign results in more sales overall. So, the Test campaign can be used to market a specific product to a specific audience, and the Control campaign can be used to market multiple products to a wider audience.

