# 🍔 Food Delivery ecommerce (Swiggy) Sales Opeartion and Revenue Analysis using SQL & Dimensional Modelling  

## 📌 Project Overview  
This project performs an **enterprise-grade SQL Sales Analysis** on Swiggy-like food delivery data using a **Dimensional Modelling approach (Star Schema)**.  
The goal is to uncover key business drivers behind **revenue growth, demand patterns, cuisine performance, restaurant dominance, and customer spending behavior**.  

<br>

## 🎯 Business Objective  
Analyze food delivery sales data to uncover:  
- **Revenue drivers** across cities/states  
- **Demand patterns** over time (month/quarter/weekday)  
- **Cuisine & restaurant dominance** in order volume  
- **Customer spending segments (price bands)**  
- Relationship between **ratings and order behavior**  

<br>

## ❓ Key Business Questions Answered  
✅ Which **cities and states** drive maximum revenue?  
✅ What **cuisines and restaurants** dominate order volume?  
✅ How does demand vary across time (**Month / Quarter / Weekday**) ?  
✅ What **price bands** contribute most to orders?  
✅ How do **ratings correlate** with order frequency?  

<br>

## 🏗️ Data Engineering & Modelling Approach  
This project follows a structured, real-world data pipeline approach:

### 1️⃣ Data Cleaning & Preparation  
Handled:  
- Null values & blanks  
- Duplicates removal  
- Standardization of categorical columns  
- Type conversions & constraints  

<br>

### 2️⃣ Dimensional Modelling (Star Schema)  
Designed a **Star Schema** for scalable analytics:  
- 1 Fact Table  
- 5 Dimension Tables  

<br>

### 3️⃣ Keys & Relationships  
Implemented:  
- **Surrogate Keys** for all dimensions  
- **Foreign Key relationships** for fact-dimension linkage  
- Strong integrity for analytical querying  

<br>

## 🧩 Schema Design (Star Model)  
**Fact Table:**  
- `fact_swiggy_orders` (captures transactional/order-level activity)

**Dimension Tables:**  
- `dim_restaurant`  
- `dim_category`  
- `dim_location`  
- `dim_date`
- `dim_dish`

<br>

## 📊 Core KPIs Built  
The project tracks the following business KPIs:

- **Total Orders**  
- **Total Revenue (INR Million)**  
- **Average Dish Price**  
- **Average Rating**  

<br>

## 🔍 Advanced Analysis Performed  
This project includes deep analytical breakdowns such as:

### 📈 Time-Series Trend Analysis  
- Monthly Revenue & Orders trend  
- Quarterly growth patterns  
- Yearly performance comparison  

<br>

### 🌍 Location Performance Analytics  
- Revenue contribution by **State**  
- Top-performing **Cities**  
- Demand hotspot mapping  

<br>

### 🍽️ Restaurant & Cuisine Performance  
- Top restaurants by order volume  
- Most profitable restaurants  
- Category-wise order & rating distribution  

<br>

### 💳 Customer Spending Buckets  
Customer segmentation based on dish/order value:  
- Low spenders  
- Mid spenders  
- High spenders  
- Premium customers  

<br>

### ⭐ Rating & Quality Correlation  
- Rating distribution analysis  
- Cuisine quality mapping  
- Relationship between **high ratings vs repeat order frequency**  

<br>

## 🛠️ Skills Demonstrated  
✅ **SQL Analytics**  
- CTEs  
- Window Functions  
- Joins  
- Aggregations  
- Case When logic  
- KPI computations  

<br>

✅ **Dimensional Modelling**  
- Star Schema design  
- Surrogate key creation  
- Fact-dimension mapping  
- Data warehouse mindset  

<br>

✅ **Business Thinking**  
- KPI design & definition  
- Revenue insights  
- Demand & customer behavior analytics  
- Analytical storytelling  

<br>

## 📂 Project Deliverables  
This repository contains:  
- SQL scripts for cleaning & transformations  
- Dimensional schema creation scripts  
- KPI queries  
- Advanced analytical queries (time-series, rating correlation, segmentation)  
- Documentation / Notes  

<br>

## 🚀 Outcome / Impact  
This analysis enables business stakeholders to:  
- Identify **revenue-dominant geographies**  
- Scale high-performing cuisines & restaurants  
- Optimize **pricing strategy via price bands**  
- Predict demand based on seasonality/weekdays  
- Improve quality by linking **ratings with frequency & cuisine performance**  

<br>

⚠️ Note: This project is for educational and analytical purposes only and is not affiliated with Swiggy 
## 🧠 Author  
**Deepanshu Gupta**  
📌 Data Analytics | SQL | Business Intelligence | Dimensional Modelling  
Linkedin - https://www.linkedin.com/in/deepanshu-gupta-3ab3861b8/

<br>




