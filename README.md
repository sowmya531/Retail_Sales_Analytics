# 🚀 SQL Retail Analytics Project

## 📊 Data Understanding
- Calculated total number of transactions
- Analyzed total revenue generated
- Identified unique customers (registered vs active)
- Computed average order value
- Evaluated total quantity sold
- Found minimum and maximum sales
- Analyzed average discount
- Examined sales distribution across stores and categories
- Tracked daily transaction counts

---

## 🧹 Data Cleaning
- Replaced NULL values using NVL
- Counted missing (NULL) values
- Calculated net revenue (amount - discount)
- Handled missing quantity values
- Used COALESCE for multiple NULL handling
- Created cleaned revenue columns
- Calculated percentage of missing data
- Flagged missing vs non-missing records
- Prepared final dataset for analysis

---

## 🔍 Filtering (WHERE Clause)
- Filtered recent transactions (last 30 days)
- Identified high-value sales (>5000)
- Extracted sales within specific ranges
- Filtered data by store and category
- Excluded specific categories
- Identified high discount transactions
- Analyzed low quantity sales
- Retrieved latest transactions

---

## 📦 Aggregation (GROUP BY)
- Calculated revenue per store and category
- Analyzed customer-wise revenue
- Computed monthly and daily revenue trends
- Found average sales per store
- Evaluated total quantity per category
- Calculated total discounts per store
- Counted transactions per store

---

## 🎯 HAVING Clause
- Identified customers with high revenue
- Found stores exceeding revenue thresholds
- Filtered categories based on average sales
- Identified frequent customers
- Detected stores with high discount usage
- Analyzed low-performing categories

---

## ⚙️ CASE WHEN
- Classified customers (High / Medium / Low spenders)
- Categorized transactions (Big / Small)
- Created discount flags
- Segmented stores based on revenue
- Categorized customers by frequency
- Created sales buckets
- Identified premium customers
- Marked high-value transactions

---

## 🔗 Joins
- Combined sales with customers, stores, and products
- Analyzed customer purchases across stores
- Calculated category-wise revenue
- Identified customers visiting multiple stores
- Found store-wise customer counts
- Detected missing relationships
- Generated customer-store revenue insights

---

## 🪟 Window Functions
- Calculated total spend per customer
- Ranked customers based on revenue
- Identified top customers per store
- Computed running totals of sales
- Used LAG and LEAD for comparisons
- Analyzed sales growth trends
- Calculated moving averages
- Ranked stores by performance

---

## 🧩 NTILE (Segmentation)
- Divided customers into segments (quartiles)
- Identified top 25% customers
- Identified bottom 25% customers
- Segmented stores based on revenue
- Created customer quartiles
- Built marketing segments (Premium / Standard / Basic)

---

## 🥇 FIRST_VALUE
- Identified highest sale per customer
- Found top-performing transactions
- Compared sales within partitions

---

## 🥉 LAST_VALUE
- Identified lowest sale per customer
- Compared transactions with minimum values
- Analyzed performance gaps within groups
