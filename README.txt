# Brazilian-Ecommerce-ML-Analysis

## Project Overview

The dataset, graciously provided by Olist, the largest department store in Brazilian marketplaces, focuses on e-commerce activities in Brazil. Olist connects small businesses nationwide, facilitating sales through the Olist Store with streamlined logistics. After a customer's purchase, sellers are notified to fulfill orders, and customers subsequently receive satisfaction surveys. This dataset, covering 100,000 orders from 2016 to 2018 across various Brazilian marketplaces, serves as a valuable resource for analysts and researchers aiming to gain insights into the Brazilian e-commerce landscape, identify growth opportunities, and optimize operations.

## Overall Steps:
1. Installing & Importing Dependencies
	- Import necessary libraries for data manipulation, visualization, and machine learning.
	- Connect using kaggle AUTH (direct)
	- Extracting ZIP files
	- Joining file using pyspark dataframe
2.  Exploratory Data Analysis
	- What payment type has the biggest total payment ? 
	- What payment type that frequently used ?
	- How's the daily transaction trend ? is there any anomali ?
	- How's the rating AOV ?
	- Delay histogram for review_score
	- Highest sales for product based on quantity
	- Customer-city wordcloud
	- Seller and buyer trend
3. Feature Engineering
	- Missing value handling
	- Drop un-necessary features
4. Machine Learning (supervised)
	- Decision tree classifier
	- Random forest

## Requirements :
matplotlib : 3.7.1
matplotlib-inline : 0.1.6
pandas : 1.5.3
pip : 23.1.2
pyspark : 3.5.0
requests : 2.31.0
scikit-learn : 1.2.2
wordcloud : 1.9.2

#Tags 
ecommerce, pyspark, kaggle, analysis, 