# PHASE 2 — ER Diagram

This section explains how the pizza sales database is organized and how the tables are connected to each other.

The database is designed to store order information clearly and make analysis easy.

---

## Tables in the Database

There are four main tables used in this project.

---

### orders
This table stores basic information about each order.

- order_id  
- order_date  
- order_time  

Each row represents one order placed by a customer.

---

### order_details
This table stores details about the pizzas ordered in each order.

- order_details_id  
- order_id  
- pizza_id  
- quantity  

This table links orders and pizzas and shows how many pizzas were ordered.

---

### pizza
This table stores information about pizza size and price.

- pizza_id  
- pizza_type_id  
- size  
- price  

Each row represents a pizza of a certain size.

---

### pizza_types
This table stores general information about each pizza type.

- pizza_type_id  
- name  
- category  
- ingredients  

This table helps group pizzas into categories like vegetarian or chicken.

---

## How the Tables Are Connected

- One order can have many order details  
- One pizza can appear in many order details  
- One pizza type can have many pizzas  

These connections help avoid repeating the same data and keep the database clean.

---

## Summary

This database structure makes it easy to analyze sales, revenue, and customer ordering patterns using SQL.
