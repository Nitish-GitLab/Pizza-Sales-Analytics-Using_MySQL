# Pizza Sales Analysis using MySQL

A SQL project that analyses pizza sales data to answer 10 business questions about revenue, best sellers, order sizes and peak hours.

## Tables
`orders`, `order_details`, `pizzas`, `pizza_types`

## SQL concepts used
JOINs (2 and 3 tables), GROUP BY, aggregate functions (SUM, COUNT, AVG, ROUND), subqueries, window functions (`SUM() OVER`), `HOUR()`

## Questions answered
1. Total revenue from pizza sales
2. Highest-priced pizza
3. Most common pizza size ordered
4. Top 5 most ordered pizza types
5. Total quantity ordered per pizza category
6. Distribution of orders by hour of the day
7. Category-wise distribution of pizzas
8. Average number of pizzas ordered per day
9. Top 3 pizza types by revenue
10. Cumulative revenue over time

## Key findings
- Total revenue: 817,860.05; about 138 pizzas ordered per day
- Large (L) is the most ordered size (18,526 orders)
- The Classic Deluxe Pizza leads in quantity (2,453), while The Thai Chicken Pizza earns the most revenue (43,434.25)
- The Classic category sells the most pizzas (14,888)
- Orders peak around 12 PM to 1 PM and 5 PM to 6 PM

## Files
- `pizza_sales_queries.sql`: all 10 queries
- `Pizza_Sales_Analysis_MySQL.pdf`: slides with each question, code and output

## Run it
Load the four tables into a MySQL database, then run the queries in `pizza_sales_queries.sql`.
