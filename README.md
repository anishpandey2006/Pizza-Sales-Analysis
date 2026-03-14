# Pizza-Sales-Analysis
Analyzed a pizza sales dataset using SQL &amp; MySQL Workbench. Worked with 4 tables covering 2015 sales data. Wrote 10 queries using SELECT, WHERE, JOIN, GROUP BY, SUM, AVG &amp; more. Key finding: 49,574 pizzas sold, avg price $16.44, most expensive — The Greek XXL @ $35.95.


# 🍕 Pizza Sales Analysis — SQL Project

## Project Overview
Analyzed a pizza restaurant dataset using SQL (MySQL).  
The dataset contains **4 tables** with sales records from **2015**.

## Tables
| Table | Description |
|---|---|
| orders | Order ID, date, time |
| order_details | Order items and quantity |
| pizzas | Pizza ID, size, price |
| pizza_types | Pizza name, category, ingredients |

## Tools Used
- **MySQL** — Query execution
- **MySQL Workbench** — IDE

## Queries Covered
| Q# | Topic | Concepts |
|---|---|---|
| Q1 | Unique pizza categories | SELECT DISTINCT |
| Q2 | Pizza ingredients with NULL handling | COALESCE |
| Q3 | Pizzas missing price | IS NULL |
| Q4 | Orders on specific date | WHERE |
| Q5 | Pizzas by price | ORDER BY DESC |
| Q6 | Pizzas in L or XL size | IN |
| Q7 | Orders on date or after 8 PM | OR |
| Q8 | Total pizzas sold | SUM |
| Q9 | Average pizza price | AVG, ROUND |
| Q10 | Total order value per order | JOIN, GROUP BY |

## Key Insights
- 🍕 Total pizzas sold — **49,574**
- 💰 Average pizza price — **$16.44**
- 👑 Most expensive pizza — **The Greek XXL @ $35.95**
- 📦 4 categories — Chicken, Classic, Supreme, Veggie
