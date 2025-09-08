# coffee-sales-analysis

# Coffee Sales Analysis ☕📊

This project analyzes coffee sales data from `index.csv`. It shows how to clean, explore, visualize, and forecast sales in a simple, step-by-step way.

---

## 🔹 Project Overview
- Clean transaction data (`date`, `datetime`, `coffee_name`, `money`, `card`, `cash_type`).
- Create new features like `month`, `weekday`, and `hour`.
- Explore sales trends by product, day, week, month, and payment method.
- Build simple visualizations (line charts, bar charts).
- Forecast future sales (next 1, 7, and 30 days) using Holt-Winters model.
- Look up customer purchase history by `card` ID.

---

## 🔹 Key Analysis
1. **Top Products** – Which coffees earn the most revenue and are most popular.
2. **Daily/Weekly/Monthly Trends** – Transactions and revenue patterns over time.
3. **Hourly & Weekday Patterns** – Busiest times of day and days of the week.
4. **Payment Mix** – Proportion of cash vs. card transactions.
5. **Forecasting** – Predicts revenue and transactions for the next 1, 7, and 30 days.
6. **Customer Behavior** – Last 10 purchases, favorite coffees, and total spend for each customer.

---

## 🔹 Visualizations
- Daily revenue and transactions (line charts).
- Revenue and transactions by coffee type (bar charts).
- Transactions by hour of day and day of week.
- Payment mix proportions.

---

## 🔹 Forecasting
- Uses **Holt-Winters Exponential Smoothing** for time series forecasting.
- Forecasts short-term sales:
  - **Next 1 day**
  - **Next 7 days**
  - **Next 30 days**
- Helps plan **inventory, staff scheduling, and promotions**.

---

## 🔹 Customer Insights
- Check history of any customer (using `card` ID).
- See their **total spend, favorite coffees, and last purchases**.
- Useful for **loyalty programs and personalized offers**.

---

## 🔹 How to Run
1. Clone the repo and add your dataset `index.csv`.
2. Install requirements:
   ```bash
   pip install -r requirements.txt
