# Innomatics-Research-Labs-Advanced-GenAI-Internship-Entrance-Test
📊 Food Delivery Data Integration & Analysis Project
📁 Project Overview

This project simulates a real-world food delivery system by combining data from multiple sources and formats. The goal is to build a unified dataset that can be analyzed to understand order trends, user behavior, restaurant performance, and revenue patterns.

Students will practice:

Loading data from CSV, JSON, and SQL formats

Performing joins across datasets

Creating a final analytical dataset

Answering business-driven questions using data

📂 Files Provided
1️⃣ orders.csv — Transactional Data

Contains individual food orders placed by users.

Order ID

User ID

Restaurant ID

Order date

Order amount

City

2️⃣ users.json — User Master Data

Contains user-level information.

User ID

User name

Membership type (Gold / Regular)

City

3️⃣ restaurants.sql — Restaurant Master Data

Contains restaurant-related details.

Restaurant ID

Restaurant name

Cuisine type

Rating



✅ Step 1: Load CSV Data

Read transactional order data from orders.csv.

✅ Step 2: Load JSON Data

Load user master data from users.json.

✅ Step 3: Load SQL Data

Extract restaurant data from restaurants.sql.

✅ Step 4: Merge the Data

Perform Left Joins to retain all order records:

orders.user_id → users.user_id

orders.restaurant_id → restaurants.restaurant_id

This ensures:

Every order is preserved

Missing user or restaurant data appears as NaN

✅ Step 5: Create Final Dataset

The final dataset combines:
Order details

User information

Restaurant information

📊 Final Dataset – What Students Should Analyze

Using final_food_delivery_dataset.csv, students should explore:

📈 Order Trends

Daily, monthly, and quarterly order volume

Seasonality in revenue

👥 User Behavior

Distinct users placing orders

Order frequency by membership type

Gold vs Regular user contribution

🌆 City & Cuisine Performance

Top revenue-generating cities

Cuisine-wise order volume and revenue

Cuisines with fewer restaurants but high revenue

⭐ Membership Impact

Revenue contribution by Gold vs Regular members

Average order value comparison

💰 Revenue Analysis

Highest revenue quarters

Restaurant rating vs revenue

High-value restaurants with low order counts
