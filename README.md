# skincare
# Sephora Product Info Dataset

This repository contains a comprehensive dataset of beauty and fragrance products from Sephora. It includes detailed information about various brands, pricing, customer ratings, and popularity metrics.

DATASET OVERVIEW:
The dataset provides insights into the beauty market, focusing on product performance and consumer interest through ratings and "loves" counts.
- **File Name:** `product_info.csv`
- **Primary Category:** Fragrance, Bath & Body, etc.
- **Total Columns:** 9 Key Metrics

DATA DICTIONARY (Column Descriptions)
| Column Name | Description |
| :--- | :--- |
| `product_id` | Unique identifier for each product. |
| `product_name` | The full name of the beauty product. |
| `brand_id` | Unique ID for the brand. |
| `brand_name` | The name of the brand (e.g., NEST New York, 19-69). |
| `loves_count` | Number of users who added the product to their "Loves" list. |
| `rating` | Average customer rating. |
| `reviews` | Total number of customer reviews. |
| `price_usd` | Price of the product in US Dollars. |
| `primary_category` | The main category of the product. |

You can easily load and analyze this dataset using Python:

```python
import pandas as pd

# Load the dataset
df = pd.read_csv('product_info.csv')

# View the first few rows
print(df.head())

Analysis Goals
Brand Popularity: Identify which brands have the highest "loves_count".

Pricing Analysis: Compare prices across different product categories.

Rating Trends: Analyze the relationship between the number of reviews and the average rating.
