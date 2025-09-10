# 🍕 Pizza Sales Data Analysis

## 📚 Project Overview  
This project involves performing comprehensive data analysis on pizza sales using SQL and Excel to generate actionable business insights. The goal was to analyze sales trends, customer ordering patterns, product performance, and key metrics to help the business optimize revenue and inventory management.

## 🎯 Objective  
To analyze pizza sales data and generate key performance indicators (KPIs), uncover sales trends by time and category, and identify top and bottom performing products for informed business decisions.

---

## ⚡ Key Features

- **KPI Analysis:**  
  Calculated critical business metrics such as Total Revenue, Average Order Value, Total Pizzas Sold, Total Orders, and Average Pizzas Per Order using SQL.

- **Trend Analysis:**  
  Analyzed order patterns by day of the week and hour of the day to uncover peak ordering times and customer behavior insights.

- **Sales Breakdown:**  
  Computed percentage of sales by pizza category and size, providing a clear view of product performance in terms of revenue contribution.

- **Product Performance:**  
  Identified top 5 and bottom 5 best-selling pizzas based on quantity sold to help guide inventory and marketing strategies.
---

## 🚀 How It Works

1. **Data Aggregation:**  
   Used SQL to compute KPIs such as Total Revenue, Average Order Value, and Average Pizzas Per Order directly from the sales data.

2. **Trend Analysis:**  
   Applied SQL queries to analyze daily and hourly trends in orders, helping the business understand when customers are most active.

3. **Sales Distribution:**  
   Generated percentage distribution of sales by pizza category and size to highlight which products drive the most revenue.

4. **Product Ranking:**  
   Retrieved top and bottom 5 pizzas based on total quantity sold to identify bestsellers and underperforming items.

---

## 📊 KPI Explanation

### ✅ 1. Total Revenue
- **Definition:**  
  The total amount of money generated from all pizza orders.
- **Formula (SQL):**  
  `SUM(total_price)`
- **Business Impact:**  
  Measures overall sales performance and tracks revenue growth over time.

  
 <img width="229" height="105" alt="Total Revenue" src="https://github.com/user-attachments/assets/fc1593c8-4952-4213-a26d-c4ed686e0685" />


---

### ✅ 2. Average Order Value (AOV)
- **Definition:**  
  The average amount spent by customers per order.
- **Formula (SQL):**  
  `SUM(total_price) / COUNT(DISTINCT order_id)`
- **Business Impact:**  
  Indicates customer spending behavior. A higher AOV suggests customers are ordering more or selecting higher-priced items.

  
  <img width="244" height="106" alt="Avg Order Value" src="https://github.com/user-attachments/assets/bf20f303-0070-42f9-89dc-6d9bea1735ad" />



---

### ✅ 3. Total Pizzas Sold
- **Definition:**  
  The total number of pizzas sold across all orders.
- **Formula (SQL):**  
  `SUM(quantity)`
- **Business Impact:**  
  Helps in understanding overall sales volume and informs inventory and supply planning.

  
<img width="249" height="108" alt="Total Pizza Sold" src="https://github.com/user-attachments/assets/375fd1d5-a796-420f-9c5c-e7d4200202bd" />

---

### ✅ 4. Total Orders
- **Definition:**  
  The total number of distinct orders placed.
- **Formula (SQL):**  
  `COUNT(DISTINCT order_id)`
- **Business Impact:**  
  Tracks customer activity and demand trends, useful for marketing and operational decisions.

  
<img width="252" height="102" alt="Total Order" src="https://github.com/user-attachments/assets/40ade081-8e31-4f6a-a7f2-d8a85eb318e4" />

---

### ✅ 5. Average Pizzas Per Order
- **Definition:**  
  The average number of pizzas ordered per customer order.
- **Formula (SQL):**  
  `SUM(quantity) / COUNT(DISTINCT order_id)`
- **Business Impact:**  
  Helps understand customer ordering patterns and whether they tend to order multiple pizzas per order, influencing promotional strategies.

  
<img width="260" height="113" alt="Avg Pizza per order" src="https://github.com/user-attachments/assets/d05a6d07-fe92-44e1-91d5-117cac68bbc8" />

---

## 📊 Sample Insights

- Identification of peak order hours and days of the week.  
- Insights into revenue contribution by product category and size.  
- Clear visibility into top-performing and low-performing pizza items.

Dashborad:
<img width="2065" height="1190" alt="image" src="https://github.com/user-attachments/assets/ce1d730f-b9db-4d71-a867-da9ad0f3836f" />



---

## ✅ Conclusion

This project demonstrates the power of SQL in performing robust sales analysis and deriving business insights from large datasets. It helps decision-makers optimize pricing, inventory, and marketing strategies based on real sales data trends.


