# cusomer_behaviour_analysis
# Customer Shopping Behaviour Analysis

## 📌 Project Overview
This is an end-to-end Data Analytics project that analyzes customer shopping behavior using transactional data of **3,900 purchases**. The goal is to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to support data-driven business decisions.

## 🛠️ Tools & Technologies
- **Python** (Pandas, NumPy) – Data cleaning, EDA & Feature Engineering
- **SQL** (PostgreSQL / MySQL) – Business analysis & complex queries
- **Power BI** – Interactive dashboard & visualization
- **Jupyter Notebook** – Analysis workflow

## 📂 Dataset
- **Rows**: 3,900  
- **Columns**: 18  
- **Key Features**:
  - Customer demographics (Age, Gender, Location, Subscription Status)
  - Purchase details (Item, Category, Purchase Amount, Season, Size, Color)
  - Shopping behavior (Discount, Promo Code, Previous Purchases, Frequency, Review Rating, Shipping Type)

## 🔍 What I Did

### 1. Data Cleaning & Preparation (Python)
- Handled missing values in Review Rating (imputed with category-wise median)
- Standardized column names to snake_case
- Created new features: `age_group` and `purchase_frequency_days`
- Removed redundant columns after consistency checks
- Loaded cleaned data into SQL database

### 2. Business Analysis (SQL)
Answered key business questions including:
- Revenue by Gender
- High-spending discount users
- Top 5 products by average rating
- Shipping type comparison (Standard vs Express)
- Subscribers vs Non-subscribers performance
- Discount-dependent products
- Customer Segmentation (New / Returning / Loyal)
- Top 3 products per category
- Repeat buyers & subscription relationship
- Revenue contribution by Age Group

### 3. Dashboard (Power BI)
Built an interactive dashboard showing:
- Key KPIs (Average Purchase Amount, Total Customers, Average Review Rating)
- Subscription Status distribution
- Revenue & Sales by Category
- Revenue & Sales by Age Group
- Filters for Gender, Category, Shipping Type, and Subscription Status

### 4. Business Recommendations
- Boost subscription conversion with exclusive benefits
- Launch loyalty programs to move customers into the “Loyal” segment
- Review discount policy to protect margins
- Highlight top-rated and best-selling products in marketing campaigns
- Focus marketing efforts on high-revenue age groups and Express shipping users

## 📊 Key Insights
- Male customers generated significantly higher revenue than female customers
- Clothing is the top revenue-generating category
- Young Adults contribute the highest revenue among age groups
- Only ~27% of customers are subscribers
- Majority of customers fall into the “Loyal” segment


## 🚀 How to Run
1. Clone the repository
2. Open the Jupyter Notebook and run the Python analysis
3. Execute the SQL queries in your preferred database
4. Open the Power BI file (`.pbix`) to explore the interactive dashboard

## 📈 Skills Demonstrated
- Data Cleaning & Feature Engineering
- Exploratory Data Analysis (EDA)
- Advanced SQL (Aggregations, Window Functions, Segmentation)
- Business Problem Solving
- Data Visualization & Dashboarding
- Storytelling with data

---
**Author**: Manish Kumar  
**Role**: Aspiring Data Analyst
