# Advanced EDA & Feature Engineering

## About This Project

This project is part of my Data Science internship at DecodeLabs.

In this project, I worked on a real-world e-commerce dataset and focused on understanding, cleaning, and preparing the data before applying a machine learning model.

The main goal was to learn how to deal with missing values, identify outliers, create useful features, and finally train a machine learning model.

## Dataset

The dataset contains e-commerce order information such as:

- Order ID
- Date
- Customer ID
- Product
- Quantity
- Unit Price
- Payment Method
- Order Status
- Items in Cart
- Coupon Code
- Referral Source
- Total Price

### 1. Data Cleaning

First, I checked the dataset for:

- Missing values
- Duplicate rows
- Data types
- Basic information about the columns

There were 309 missing values in the `CouponCode` column.

I filled the missing categorical values using the most frequent value.

### 2. Feature Engineering

I created new features from the existing columns:

- `OrderYear`
- `OrderMonth`
- `OrderDayOfWeek`
- `IsWeekend`
- `QuantityToCartRatio`
- `PricePerCartItem`
- `IsHighValueOrder`

These features helped me practice how existing data can be transformed into more useful information.

## Machine Learning

After completing the data cleaning and feature engineering, I trained a:

**Random Forest Regressor**

The target variable was:
TotalPrice
