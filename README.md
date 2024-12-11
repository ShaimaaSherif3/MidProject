# Craigslist Cars and Trucks Dataset Analysis

This project analyzes the Craigslist Cars and Trucks dataset to uncover trends, clean the data, and answer key business questions

## Overview

This project performs an exploratory data analysis (EDA) on the Craigslist Cars and Trucks dataset. The goal is to clean the dataset, identify trends, and answer key business questions related to the used car market.

## Project Steps

The project consists of the following steps:
1. *Data Download and Extraction*: The dataset is downloaded from Kaggle and extracted.
2. *Data Assessment*: The dataset is inspected for issues like missing values, duplicates, and outliers.
3. *Data Cleaning*: Cleaning the data by handling missing values, removing duplicates, and addressing outliers.
4. *Exploratory Data Analysis (EDA)*: Analyzing the data and answering key business questions.
5. *Save Cleaned Data*: Exporting the cleaned dataset for future use

## Technologies Used

- *Python* for data manipulation and analysis.
- *Libraries*: pandas, numpy, matplotlib, seaborn.
- *Jupyter Notebook* for code execution and documentation.
- *Kaggle API* for downloading the dataset.

## Dataset Description

The dataset contains the following key columns:
- price: The listing price of the vehicle.
- year: The year the vehicle was manufactured.
- manufacturer: The brand of the car.
- odometer: Mileage of the car in miles.
- condition: The condition of the car (e.g., new, good, fair).
- state: The state where the car is listed.

Source: [Craigslist Cars and Trucks Dataset on Kaggle](https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data)

## Business Questions Addressed

1. What are the most popular car brands listed on Craigslist?
2. What is the average price of cars based on their brand?
3. How do car prices vary by condition?
4. What is the distribution of car listingsby state?
5. What is the relationship between odometer readings and price?
6. How does car type influence price?
7. What is the most common fuel type?

#### *Content:*
- Summary of the most important findings from the project.

#### *Example:*
```markdown
## Key Insights
- *Brand Popularity:* Toyota, Ford, and Chevrolet dominate the listings.
- *Pricing Trends:* Luxury brands have higher average prices, while affordable brands dominate the lower price range.
- *Condition Impact:* "Like new" cars are priced significantly higher than those in "fair" condition.
- *Geographical Trends:* Listings are concentrated in large states like California and Texas

## Future Work
- Build predictive models to estimate car prices based on features.
- Develop an interactive dashboard for dynamic visualizations.
- Analyze the impact of listing dates on car price

## Credits & License
- Dataset: [Craigslist Cars and Trucks Dataset on Kaggle](https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data)
- License: This project is licensed under the MIT License.
