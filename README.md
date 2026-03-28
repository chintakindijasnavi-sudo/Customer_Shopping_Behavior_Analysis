## Dataset Link 
https://www.kaggle.com/datasets/bulent1025/customer-shopping-behavior

## Project Overview 
This project performs an end-to-end analysis of a retail fashion store's customer transaction data to 
uncover actionable insights around revenue drivers, customer segmentation, discount effectiveness, and product performance.
Working with a dataset of 3,900 customer records across 18 features, the analysis spans the full data workflow 
from Python-based EDA to SQL querying to an interactive Power BI dashboard.

##  Dataset Overview
The dataset contains 3900 customer transaction records with 18 features sourced from Kaggle. 
It covers customers aged 18 to 70 years with purchase amounts ranging from $20 to $100 per transaction.

# What the Data Includes
Demographics — Customer ID, Age, Gender, and Location give a clear picture of who the customers are.
Product Info — Item Purchased, Category, Size, and Color capture what customers are buying.
Transaction Details — Purchase Amount, Season, and Review Rating reflect how much was spent and how satisfied customers were.
Behavioral Signals — Subscription Status, Discount Applied, Promo Code Used, Previous Purchases, and Frequency of Purchases reveal how customers engage over time.
Logistics — Shipping Type and Payment Method round out the transactional picture.

4 product categories — Clothing, Accessories, Footwear, Outerwear
6 payment methods — PayPal, Credit Card, Cash, Debit Card, Venmo, Bank Transfer
6 shipping options — Standard, Express, Free Shipping, Store Pickup, Next Day Air, 2-Day
Purchase data captured across all 4 seasons

## Tools & Technologies
SQL (MySQL) - Business queries & analysis
Python - Data cleaning & EDA
Power BI - Dashboard & visualization

## Project Workflow
Step 1 — Data Collection
Downloaded the dataset from Kaggle as a CSV file.
Step 2 — Python EDA
Loaded the raw CSV into a Jupyter Notebook using pandas. Inspected data types, shape, and column structure.
Handled missing values, dropped irrelevant columns, and engineered a new Age Group feature by binning the Age column into meaningful segments. 
The cleaned dataset was then exported and loaded into MySQL for structured querying.
Step 3 — Data Loading into SQL
After understanding the data through EDA, imported the cleaned dataset into MySQL as customer_data table for structured querying.
Step 4 — SQL Analysis
Wrote 10 business-focused queries in MySQL to extract revenue insights, segment customers, rank products, and compare behavioral patterns.
Step 5 — Power BI Dashboard
Connected Power BI to the dataset and built an interactive dashboard to visually communicate all key findings.

## SQL Analysis
Q1. Revenue by Gender

Q2. Discount Users Who Spent Above Average

Q3. Top 5 Highest Rated Products

Q4. Shipping Type vs Average Spend

Q5. Subscriber vs Non-Subscriber Spend

Q6. Most Discounted Products

Q7. Customer Segmentation

Q8. Top 3 Products per Category

Q9. Repeat Buyers and Subscription Conversion

Q10. Revenue by Age Group

## Key Findings
The analysis revealed that male customers drive significantly more revenue than female customers, contributing over 2x the total spend. 
When it comes to age, older customers (56–70) are the highest-value segment while younger shoppers (18–25) contribute the least.
Despite having a subscription program in place, subscribers and non-subscribers spend almost the same amount per visitmeaning the program
is not influencing purchasing behavior.
Similarly, discounts are not driving higher spend — customers with and without discounts show nearly identical average purchase amounts,
suggesting margins are being lost with no real return.
Clothing dominates the product mix at 45% of total revenue, with clear hero products in every category driving the bulk of orders.
Seasonally, Fall is the strongest period while Summer consistently underperforms.
Perhaps the most critical finding — loyal repeat buyers are not converting to subscriptions. With nearly 1,800 repeat customers
choosing to remain unsubscribed, there is a clear gap in the retention strategy that the business needs to address.


## Business Recommendations
Based on the findings, here are six actionable recommendations for the business:
1. Fix the Subscription Program :
Since subscribers spend the same as non-subscribers, the program needs stronger incentives — exclusive discounts, free shipping thresholds,
or early product access to give customers a real reason to subscribe.
2. Convert Loyal Repeat Buyers :
Nearly 1,800 repeat buyers are non-subscribers. A targeted campaign such as "You've shopped with us 6 times — unlock Premium benefits" 
could significantly grow subscription revenue without acquiring new customers.
3. Stop Blanket Discounting :
Discounts are not increasing spend — they are only cutting margins. Replace flat discounts with conditional offers to incentivize higher basket sizes instead.
4. Focus on the 56–70 Age Segment :
This is the highest-value customer group. Tailored product recommendations, personalized email campaigns, and loyalty perks designed specifically for this
segment can further grow revenue here.
5. Build a Summer Strategy :
Summer underperforms every other season by $4,000–$5,000. Targeted summer collections, flash sales, or seasonal bundles can close that gap and smooth
out revenue across the year.
6. Attract Younger Customers :
The 18–25 segment is the lowest-spending group. Social media campaigns, trend-driven products, and flexible payment options can reduce purchase friction and grow this segment over time.

## Conclusion
This project analyzes customer shopping behavior across 3,900 transactions to help a retail business better understand its customers, products, and revenue drivers.
The analysis uncovered key gaps in the store's subscription and discount strategy, identified the most valuable customer segments, and highlighted seasonal and category-level opportunities for growth. 
Working through the complete workflow — from data cleaning in Python to SQL querying to Power BI dashboarding — was a great hands-on experience that strengthened my ability to ask the right business 
questions and translate data into decisions. 

## Author 
Chintakindi Jasnavi Email: chintakindijasnavi@gmail.com 
GitHub : https://github.com/chintakindijasnavi-sudo/Customer_Shopping_Behavior_Analysis/edit/main/README.md
