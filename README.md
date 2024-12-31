# Pizza Sales Dashboard

## Overview
This repository features a **Pizza Sales Dashboard** built using **Power BI**. The dashboard provides insights into pizza sales trends, customer preferences, and business performance through key metrics, interactive charts, and visualizations.

---

## Dashboard Overview

### Home: KPIs and Trends  
![Pizza Sales Dashboard 1](./Dash1.png)

### Best/Worst Sellers: Performance Analysis  
![Pizza Sales Dashboard 2](./Dash2.png)

---

## Key Metrics and Visualizations

The dashboard tracks and analyzes essential business metrics and trends, helping stakeholders make informed decisions. It includes:

### **Key Metrics**
- **Total Revenue**: $817.9K
- **Total Orders**: 21K
- **Total Pizzas Sold**: 50K
- **Average Order Value**: $38.31
- **Average Pizzas per Order**: 2.32

### **Visualizations**
1. **Daily Order Trend**: Highlights the busiest days (Friday & Saturday) using a bar chart.
2. **Monthly Order Trend**: A line chart showcasing peak months (July & January).
3. **Sales by Pizza Category**: Displays contributions by category (Classic, Supreme, Veggie, Chicken) using a pie chart.
4. **Pizzas Sold by Category**: A funnel chart presenting the number of pizzas sold per category.
5. **Sales by Pizza Size**: A donut chart visualizing sales distribution by size (Large, Medium, Regular, X-Large).
6. **Top 5 Best Sellers**: A bar chart of pizzas with the highest revenue, quantity, and orders.
7. **Bottom 5 Sellers**: Highlights the least-performing pizzas in terms of sales and quantity.

---

## DAX Calculations

Here are the key DAX calculations used in this dashboard:

1. **Average Order Value:**
   ```DAX
   Average Order value = [Total Revenue] / [Total Order]
   ```
   Calculates the average revenue per order.

2. **Average Pizzas per Order:**
   ```DAX
   Average Pizza per Order = [Total Pizza Sold] / [Total Order]
   ```
   Computes the average number of pizzas sold per order.

3. **Total Orders:**
   ```DAX
   Total Order = DISTINCTCOUNT(pizza_sales[order_id])
   ```
   Counts the distinct number of orders.

4. **Total Pizzas Sold:**
   ```DAX
   Total Pizza Sold = SUM(pizza_sales[quantity])
   ```
   Sums up the quantity of pizzas sold.

5. **Total Revenue:**
   ```DAX
   Total Revenue = SUM(pizza_sales[total_price])
   ```
   Sums up the total revenue from sales.

---

## How to Use

1. Open the **Pizza Sales Dashboard.pbix** file in **Power BI Desktop**.
2. Load or update the data from **pizza_sales.csv**.
3. Explore the interactive visuals:
   - **Home**: View KPIs and trends.
   - **Best/Worst Sellers**: Analyze performance insights.

---

## Contact

For questions, feedback, or collaboration:

- **Name:** Bahaa Medhat Wanas  
- **Email:** [bahaawanas427@gmail.com](mailto:bahaawanas427@gmail.com)  
- **LinkedIn:** [Bahaa Wanas](https://www.linkedin.com/in/bahaa-wanas-9797b923a)  

---
