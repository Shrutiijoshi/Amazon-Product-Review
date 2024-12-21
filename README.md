# Amazon Product Reviews Analysis
This repository contains an in-depth analysis of Amazon product reviews to extract actionable insights. The project leverages datasets, statistical techniques, and visualization tools to understand trends and patterns that can enhance customer satisfaction, optimize product offerings, and boost sales.
## Table of Contents
- [Overview](#Overview)
- [Dataset](#Dataset)
- [Analysis Goals](#Analysis-Goals)
- [Technologies Used](#Technologies-Used)
- [Analysis Breakdown](#Analysis-Breakdown)
- [Getting Started](#Getting-Started)
- [Results and Insights](#Results-and-Insights)
## Overview
The online retail market is highly competitive, making it crucial to understand customer behavior, product performance, and pricing strategies. This project focuses on exploring Amazon product reviews to:
- Analyze customer feedback.
- Evaluate product ratings, discounts, and descriptions.
- Identify trends that can improve marketing and sales strategies.
## Dataset
Source : [Amazon sales dataset](https://www.kaggle.com/datasets/ahmedsayed564/amazon-sales-dataset)
### Data Dictionary
- product_id: The unique identifier for each product.
- product_name: The name of the product.
- category: The category under which the product is listed, further divided into sub-categories separated by "|".
- discounted_price: The price of the product after applying the discount.
- actual_price: The original price of the product without any discount.
- discount_percentage: The percentage of discount offered on the product.
- rating: The average rating given to the product by the customers.
- rating_count: The number of ratings the product received.
- about_product: A brief description of the product.
- user_id: The unique identifiers for users who reviewed the product, separated by commas.
- user_name: The names of users who reviewed the product, separated by commas.
- review_id: The unique identifiers for the reviews, separated by commas.
- review_title: The titles of the reviews, separated by commas.
- review_content: The content of the reviews, separated by commas.
- img_link: The link to the image of the product.
- product_link: The link to the product's page on Amazon.
## Analysis Goals
The primary objectives of this project include:
- Analyzing the impact of discounts on product ratings.
- Identifying top-rated categories and products.
- Understanding customer sentiment through reviews.
- Exploring correlations between review length, descriptions, and ratings.
- Visualizing key insights with Tableau and Python.
## Technologies Used
- Python: Data cleaning, analysis, and visualization using libraries like Pandas, Matplotlib, Seaborn.
- Excel: Quick data exploration, pivot tables, and initial charts.
- Tableau: Interactive dashboards and visualizations
## Analysis Breakdown
### 1. Discount Analysis
- Question : How does the discount percentage affect the rating of a product?
- Tools : Scatter plots (Python, Tableau), Correlation Analysis (Excel).
### 2. Category Analysis
- Question: Which category has the highest average rating?
- Tools: Grouping and aggregation (Python), Bar Charts (Tableau).
### 3. Price Analysis
- Question: Is there a correlation between price and ratings?
- Tools: Correlation analysis (Python, Excel), Scatter plots (Tableau).
### 4. Review Analysis
- Question: What are the most common words in positive and negative reviews?
- Tools: (Python,Excel).
### 5. Rating Analysis
- Question: What is the distribution of product ratings?
- Tools: Histograms (Excel, Python), Bar Charts (Tableau).
### 6. Product Analysis
- Question: Which product has the highest number of reviews and what is its rating?
- Tools: Excel, Python, Tablue.
### 7. User Analysis
- Question: Identify the top 5 users who have given the most reviews
- Tools: Excel, Python, Tableau.
### 8. Review Length Analysis
- Question : Is there a correlation between the length of a review and the rating given?
- Tools : Excel, Python
### 9. Image Analysis
- Question : Does having an image link affect the product rating?
- Tools : Excel, Python
### 10. Product Description Analysis
- Question : Can the length of the product description be correlated to the product's rating?
- Tools : Excel, Python
## Getting Started
### Prerequisites
- Python 3.x
- Libraries: Pandas, Matplotlib, Seaborn, NLTK, TextBlob
- Tableau Desktop (For visualization)
- Microsoft Excel
## Results and Insights
Key Findings:
- Discounts positively impact ratings for products under certain categories.
- Products in the Computer & Accessories category have the highest average ratings.
- Positive reviews frequently contain words like "excellent or good," while negative reviews emphasize "poor."


