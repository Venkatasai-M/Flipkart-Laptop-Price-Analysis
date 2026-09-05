# Laptop Price Analysis Using Flipkart

## Project Overview

This project focuses on collecting and analyzing laptop data from Flipkart to understand how factors such as brand, processor, RAM, storage, ratings, and discounts influence laptop prices.

Laptop listings were collected using web scraping, followed by data cleaning and Exploratory Data Analysis (EDA) to identify useful pricing and market trends.

## Objectives

- Analyze laptop prices across different brands and configurations.
- Identify the specifications that have the strongest relationship with price.
- Compare pricing based on RAM, storage, processor, and brand.
- Analyze discount and rating patterns.
- Identify value-for-money laptop configurations.

## Dataset

- Approximately **480 laptop listings**
- **20 Flipkart search pages** scraped
- Around **14 raw features**
- Multiple laptop brands and configurations

Important features include:

- Brand
- Product Name
- Current Price
- Original Price
- Discount
- Rating
- Processor
- RAM
- Storage
- Display Size
- Operating System
- GPU
- Ratings and Reviews

## Technologies Used

- Python
- Requests
- BeautifulSoup
- Pandas
- Regular Expressions (Regex)
- Matplotlib
- Seaborn
- Jupyter Notebook

## Web Scraping

Laptop listings were collected from Flipkart using **Requests** and **BeautifulSoup**.

The scraping process extracted information such as laptop name, price, discount, rating, processor, RAM, storage, display, operating system, GPU, and other specifications.

## Data Cleaning

The collected data was cleaned and prepared using Pandas and Regex.

Major cleaning steps included:

- Removing duplicate laptop listings
- Converting price and discount fields into numeric values
- Handling missing values
- Extracting RAM and storage information
- Separating ratings and reviews
- Correcting data types
- Preparing the dataset for analysis

## Exploratory Data Analysis

Univariate and bivariate analysis were performed to understand:

- Brand distribution
- Laptop price distribution
- Rating distribution
- RAM configurations
- Brand-wise pricing
- Discount vs. price
- RAM vs. price
- Correlations between numerical features

## Key Insights

- Brand and RAM were important factors associated with laptop pricing.
- RAM showed a strong positive correlation with price in the analyzed data.
- Premium brands generally had higher median prices.
- Most laptops were concentrated in the budget-to-mid price range.
- Customer ratings were generally around 4.0–4.3.
- 16GB RAM / 512GB SSD configurations provided a strong balance between specifications and price in the analyzed listings.

## Project Files

- `Laptop_Price_Analysis_Flipkart.ipynb` – Web scraping, data cleaning and EDA
- `Laptop_Price_Analysis_Project.pptx` – Project presentation

## Author

**Mada Venkata Sai**

B.Sc. Computer Science Graduate  
Aspiring Data Analyst
