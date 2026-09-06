# 🛍️ Customer Shopping Behaviour Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-8A2BE2?style=flat)

---

## 01. 📌 Project Overview

This project analyzes **3,900 customer records** to understand purchasing behaviour, customer segments, product performance, discounts, subscriptions, ratings, shipping preferences, payment methods, and purchase frequency.

The project follows an end-to-end analytics workflow:

**Raw Data → Python EDA & Cleaning → Feature Engineering → PostgreSQL/SQL Analysis → Power BI Dashboard → Insights → Recommendations**

The objective is to move from descriptive customer data toward actionable retail insights.

---

## 02. 🎯 Business Problem

The business wants to understand customer behaviour across demographics, products, discounts, reviews, subscriptions, payment methods, shipping preferences, and purchasing frequency.

### Key Business Questions

- Which customer segments contribute the most revenue?
- Which categories and products perform best?
- How does discount usage relate to purchasing behaviour?
- Which customers represent loyalty or retention opportunities?
- How do subscription and shipping preferences vary across customers?
- Which products receive the strongest customer ratings?

---

## 03. 📂 Dataset

The dataset contains **3,900 customer records** covering demographics, purchasing activity, product information, discounts, ratings, subscriptions, shipping, payment methods, and purchase frequency.

### Main Data Areas

| Area | Examples |
|---|---|
| Customer | `customer_id`, `age`, `gender` |
| Product | `item_purchased`, `category`, `size`, `color` |
| Purchase | `purchase_amount`, `previous_purchases` |
| Customer Experience | `review_rating`, `shipping_type` |
| Marketing | `discount_applied`, `subscription_status` |
| Behaviour | `frequency_of_purchases`, `payment_method` |

---

## 04. 🐍 Python — Data Preparation & EDA

Python and Pandas were used for:

- Dataset inspection
- Data cleaning
- Missing-value analysis
- Data-type review
- Column standardization
- Exploratory analysis
- Feature engineering
- Preparing the dataset for SQL analysis

### Feature Engineering

Customers were grouped into age segments including:

- Young Adult
- Adult
- Middle Aged
- Senior

Purchase-frequency categories were also converted into numerical day intervals to support frequency-based analysis.

---

## 05. 🗄️ SQL & PostgreSQL Analysis

The cleaned dataset was loaded into PostgreSQL for structured business analysis.

### Questions Answered

- Total revenue by gender
- Discounted customers spending above average
- Highest-rated products
- Average purchase amount by shipping type

### SQL Concepts Used

- `SELECT`
- `WHERE`
- `GROUP BY`
- `SUM()`
- `AVG()`
- Subqueries
- `ORDER BY`
- `LIMIT`
- `CASE WHEN`
- CTEs
- `ROW_NUMBER()`
- `PARTITION BY`

---

## 06. 🔗 Data Model

The Power BI model connects the customer dataset with an **Images** table using `Category`.

This relationship allows the dashboard to associate product/category analysis with corresponding visual assets.

---

## 07. 📊 Power BI Dashboard

The dashboard includes:

- Total customers
- Total revenue
- Average purchase amount
- Average review rating
- Revenue by age group
- Revenue by category
- Subscription status
- Customer type
- Category filtering
- Gender filtering
- Shipping-type filtering

![Customer Shopping Behaviour Dashboard](images/powerbi_dashboard.png)

---

## 08. 📌 Dashboard Snapshot

| Metric | Value |
|---|---:|
| Customers | 3.9K |
| Total Revenue | $233.1K |
| Average Purchase | $59.76 |
| Average Review | 3.75 |
| Subscribers | 27% |

---

## 09. 💡 Key Insights

### 1. Clothing Is the Strongest Revenue Category

Clothing contributes around **$100K**, making it the strongest-performing category in the dashboard.

### 2. Young Adults Lead Revenue Contribution

Young Adults contribute approximately **$62K**, the highest among the analyzed age groups.

### 3. Subscription Penetration Is Low

Only **27% of customers are subscribers**, while approximately 73% are non-subscribers.

This represents a potential opportunity to improve subscription conversion and retention.

### 4. Discounts Can Support Higher-Value Purchases

The SQL analysis identifies customers who used discounts while still spending above the overall average purchase amount, providing a basis for evaluating targeted promotional strategies.

### 5. Customer Loyalty Can Be Segmented

Customers were classified as **New, Returning, and Loyal** using previous purchase behaviour.

This provides a foundation for differentiated retention and engagement strategies.

---

## 10. 💼 Business Recommendations

### Increase Subscription Conversion

With only **27% of customers subscribed**, the business could test targeted subscription benefits for high-frequency and returning customers.

### Protect High-Performing Categories

Clothing contributes around **$100K** in revenue, so inventory planning, promotional investment, and product expansion should consider the category's strong performance.

### Target Young Adult Customers

Young Adults generate the highest revenue contribution at approximately **$62K**, making them a useful segment for targeted campaigns and product recommendations.

### Use Discounts More Strategically

Instead of broad discounting, the business could identify customers who are already capable of higher-value purchases and test personalized offers.

### Personalize Retention Strategies

New, returning, and loyal customers can be targeted differently based on their purchase history and engagement level.

> These recommendations are proposed actions based on the observed project findings; they are not measured business outcomes.

---

## 11. 🧠 Skills Demonstrated

| Area | Skills |
|---|---|
| Python | Pandas, EDA, cleaning, feature engineering |
| SQL | Aggregation, filtering, subqueries, CTEs, window functions |
| PostgreSQL | Database loading and structured analysis |
| Power BI | Dashboard development and interactive reporting |
| DAX | Measures and calculated analysis |
| Business Analytics | Customer segmentation, product analysis, recommendations |
| Visualization | KPI reporting, category comparisons, interactive filters |

---

## 12. 📂 Project Files

- `python/` — Python notebook and data preparation
- `SQL/` — PostgreSQL/SQL analysis
- `Power BI/` — Power BI dashboard
- `data/` — Source/cleaned data
- `images/` — Dashboard and analytical screenshots
- `Business Problem Document (CSB).pdf` — Business problem documentation

---

## 13. 📁 Project Structure

```text
Customer-Shopping-Behavior/
│
├── Power BI/
├── SQL/
├── data/
├── images/
├── python/
├── Business Problem Document (CSB).pdf
└── README.md
```

---

## 14. 🎓 Key Takeaway

This project demonstrates an end-to-end analytics workflow combining **Python, SQL, PostgreSQL, and Power BI** to move from raw customer data to business-oriented insights and recommendations.

---

## 👨‍💻 Author

**Adithya Ruby**

Computer Science Graduate | Data Analytics
