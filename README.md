# Customer-trend-analysis
An end-to-end data analytics project combining Python, SQL, and Power BI to decode consumer purchase behavior and guide strategic business decisions.


📘 **Project Overview**

This project uncovers actionable insights into customer shopping behavior for a retail company aiming to boost sales performance, customer satisfaction, and loyalty.
Through an end-to-end analytical pipeline, the project demonstrates how data can be transformed into strategic intelligence for marketing optimization, product positioning, and customer segmentation.

🎯 **Business Problem**

A leading retail company has observed dynamic shifts in shopping patterns across demographics, categories, and channels.
The management team seeks to answer:

“How can the company leverage consumer shopping data to identify trends, improve engagement, and optimize marketing and product strategies?”

🧩 **Objectives**

Analyze key drivers of customer purchasing decisions (discounts, reviews, seasons, etc.)

Identify high-value segments and loyalty behaviors

Compare revenue and performance across demographics and shipping preferences

Provide actionable recommendations to enhance marketing and retention

📊 **Dataset Summary**

Feature Type	Examples	Description
Demographics	Age, Gender, Location	Understand customer distribution
Behavioral Data	Discount Applied, Review Rating, Subscription Status	Track engagement and loyalty
Transactional Data	Purchase Amount, Item Purchased, Category, Season	Measure spending and trends
Size & Scope	3,900 records × 18 columns	Cleaned and modeled for analysis

🧼Data Cleaning:

Imputed 37 missing values in review_rating using median per product category

Created age_group and purchase_frequency_days

Removed redundant variables and standardized columns

🐍 1. **Data Preparation & EDA** **(Python)**

Imported and explored dataset using Pandas, NumPy, and Matplotlib

Identified missing data and outliers

Performed feature engineering and binning

Exported the cleaned dataset to PostgreSQL for advanced SQL analysis

📘 Notebook: Customer_Shopping_Behavior_Analysis.ipynb

🧮 2. **Business Analysis (SQL)**

All SQL queries simulate real-world business intelligence tasks.

Analysis	Description
Revenue by Gender	Identified gender-based spending patterns
High-Spending Discount Users	Customers who use discounts yet spend above average
Top Products by Rating	Products with the highest customer satisfaction
Shipping Type Impact	Compared average order value by shipping method
Subscription Impact	Compared spend between subscribers vs non-subscribers
Customer Segmentation	Classified New, Returning, and Loyal buyers
Revenue by Age Group	Quantified contribution of each demographic

📄 SQL File: customer_behavior_sql_queries.sql

📈 3. **Dashboard Visualization (Power BI)**

A fully interactive Power BI dashboard showcases insights visually for quick decision-making.

Key Visuals:

Gender-based Revenue Breakdown

Product Ratings & Discount Dependency

Subscriber vs Non-Subscriber Spend

Age Group Revenue Heatmap

Customer Segment Distribution

📊 Dashboard: customer_behavior_dashboard.pbix

💡 **Key Insights**

Insight	Impact
👩‍💼 Female customers generate slightly higher revenue	Optimize female-focused campaigns
💸 Discount users can be premium buyers	Introduce “Smart Saver” premium offers
🚀 Express shipping users spend 12% more	Incentivize express delivery with loyalty points
💎 Subscribers contribute 45% of total revenue	Enhance subscriber-exclusive benefits
🔁 50% of customers are first-time buyers	Build onboarding offers to convert them to returning buyers
🧭 Business Recommendations

Boost Subscriptions – Offer exclusive perks and tier-based plans

Loyalty Program – Reward high-frequency buyers with cashback or coupons

Targeted Marketing – Focus on high-value demographics and segments

Optimize Discounts – Balance discount strategy to protect margins

Product Positioning – Highlight top-rated and best-selling products

🧠 **Tech Stack**

Layer	Tools Used	Purpose
Data Preparation:	Python (Pandas, NumPy, Matplotlib)	Data cleaning, EDA
Database Analysis:	PostgreSQL	Querying and BI analysis
Visualization:	Power BI	Interactive reporting
Documentation:	Markdown, PowerPoint	Communication of insights
🗂️ **Repository Structure**

📁 Customer-Shopping-Behavior-Analysis/
│
├── 📄 Business Problem Document.pdf
├── 📊 Customer_Shopping_Behavior_Analysis.ipynb
├── 🗃️ customer_behavior_sql_queries.sql
├── 📈 customer_behavior_dashboard.pbix
├── 📘 Customer Shopping Behavior Analysis.pdf
├── 📑 Customer-Shopping-Behavior-Analysis.pptx
└── 📂 README.md

🚀 **Results**

✅ Delivered end-to-end workflow from raw data → insights → visualization
✅ Revealed 5+ critical revenue-driving factors
✅ Designed a scalable analytics framework replicable for future datasets
✅ Demonstrated cross-tool integration across Python, SQL, and Power BI

💼 **Impact Summary**

Business Value: Data-driven recommendations for marketing and customer retention

Technical Value: Demonstrated proficiency in full analytics stack

Career Value: Portfolio-ready project showcasing analytical thinking, technical depth, and storytelling
