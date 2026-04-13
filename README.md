# skincare
SEPHORA PRODUCT INFO DATASET
This repository contains a comprehensive dataset of beauty and fragrance products from Sephora. It includes detailed information about various brands, pricing, customer ratings, and popularity metrics.

DATASET OVERVIEW:
The dataset provides insights into the beauty market, focusing on product performance and consumer interest through ratings and "loves" counts.

File Name: product_info.csv

Primary Category: Fragrance, Bath & Body, etc.

Total Columns: 9 Key Metrics

DATA DICTIONARY:
 Column Name     Description
product_id       Unique identifier for each product.
product_name     The full name of the beauty product.
brand_name      "The name of the brand (e.g., NEST New York)."
loves_count     "Number of users who ""loved"" the product."
rating           Average customer rating.
price_usd        Price of the product in USD.

ANALYSIS GOALS
BRAND POPULARITY: Identify which brands have the highest "loves_count".

PRICING ANALYSIS: Compare prices across different product categories.

RATING TRENDS: Analyze the relationship between the number of reviews and the average rating.

TECH STACK
This project uses the following tools and libraries for data processing and analysis:
LANGUAGE: Python
LIBRARIES: Pandas (Data Manipulation), NumPy, Matplotlib/Seaborn
SPREADSHEET TOOL: Microsoft Excel (for initial data cleaning and quick filtering)
IDE: Jupyter Notebook / VS Code / Google Colab

HOW TO USE
You can interact with this dataset in two ways:

1. USING MICROSOFT EXCEL
* Open `product_info.csv` directly in Excel.
* Use **Filters** to sort by `price_usd` or `rating`.
* Create **Pivot Tables** to see average prices by `brand_name`.

2. USING PYTHON
To analyze this data programmatically, use the following code:

```python
import pandas as pd

# Load the dataset
df = pd.read_csv('product_info.csv')

# View the first few rows
print(df.head())

ANALYSIS GOALS
BRAND POPULARITY: Identify which brands have the highest "loves_count".

PRICING ANALYSIS: Compare prices across different product categories.

RATING TRENDS: Analyze the relationship between the number of reviews and the average rating.
