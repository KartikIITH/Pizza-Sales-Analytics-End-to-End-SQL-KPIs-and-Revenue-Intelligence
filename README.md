# Pizza-Sales-Analytics-End-to-End-SQL-KPIs-and-Revenue-Intelligence
A comprehensive SQL analytics project using a pizza restaurant dataset to compute demand patterns, pricing insights, and revenue KPIs. Includes starter, intermediate, and advanced queries covering order volumes, price leaders, category trends, hourly distributions, daily averages, and cumulative revenue analysis.


A comprehensive SQL analytics project using a pizza restaurant dataset to compute demand patterns, pricing insights, and revenue KPIs. Includes starter, intermediate, and advanced queries covering order volumes, price leaders, category trends, hourly distributions, daily averages, and cumulative revenue analysis.

Pizza Sales Analytics: End‑to‑End SQL KPIs and Revenue Intelligence 🍕

Overview 🔎

SQL analytics over 4 tables with 15+ KPIs, time‑series insights, and revenue intelligence for a pizza retailer 📊.

Dataset 🗃️

orders — order_id, date, time 📅 ⏰

order_details — order_details_id, order_id, pizza_id, quantity 📄

pizzas — pizza_id, pizza_type_id, size, price 🏷️

pizza_types — pizza_type_id, name, category, ingredients 📑

ER model 🔗

orders → order_details (1:N), pizzas → order_details (1:N), pizza_types → pizzas (1:N) ⛓️

Getting started 🚀

Create tables, load CSVs, set types (DATE, TIME, INT, DECIMAL) ✅

PostgreSQL primary; MySQL compatible with minor syntax changes 🔁

Key questions ❓

Orders total 📋, revenue 💰, highest price 🏆, most common size 📏, top‑5 pizzas 🥇

Category totals 📂, hourly orders ⏰, daily average 📅, top‑3 by revenue 🏆

Revenue share 🥧, cumulative revenue 📈, top‑3 per category 🥇

Highlights ✨

115K+ orders and 590K+ line items analyzed; accurate FK joins and standardized schema ✅

15+ KPI queries and 10+ time‑series/category views using CTEs and window functions 📐🪟

Cumulative revenue by day and revenue share; top‑3 rankings overall and by category 🏆🥧

Run queries 💻

Basic: totals, revenue, top sizes, top‑5 pizzas 📋💰

Intermediate: category totals, hourly orders, daily averages, top‑3 by revenue ⏰📅

Advanced: revenue share, cumulative revenue, top‑3 by category with ROW_NUMBER() 📈
