# Amazon-reviews-analysis
## 📌 Project Overview

This project focuses on analyzing Amazon product reviews to extract valuable insights. The data was cleaned, processed, and analyzed using SQL and Python, with visualization and reporting done in Power BI.
## 📂 Dataset Description

**The dataset contains Amazon product reviews with the following key columns:**

product_id: Unique identifier for each product

product_name: Name of the product

category: Product category

discounted_price: Price after discount

actual_price: Original price

discount_percentage: Percentage discount

rating: Product rating (out of 5)

rating_count: Number of ratings

about_product: Description of the product

user_id: Unique identifier for the reviewer

user_name: Name of the reviewer

review_id: Unique identifier for the review

review_title: Title of the review

review_content: Detailed review

img_link: Link to the product image

product_link: Link to the product page

## 🛠 Data Cleaning & Preprocessing

Issues Identified:

Prices and discounts stored as strings with currency symbols

Ratings and rating counts stored as text

Duplicate records found

Missing values in some fields
## Cleaning Steps:

Converted prices and discounts to numerical values by removing currency symbols.

Converted ratings and rating counts to numerical types.

Dropped duplicate records.

Handled missing values by imputing or removing rows where necessary.

Stored the cleaned data in SQL for easy querying.

## 📈 Power BI Dashboard

The cleaned dataset was imported into Power BI to create interactive visualizations:

* Rating distribution by category

* Top-selling products

* Price vs. discount analysis

* Review sentiment trends

🔗 Author: Veronicah Sihlangu

📅 Date: 2025-02-06

🛠 Tools Used: Python (Pandas, SQLAlchemy), SQL, Power BI

