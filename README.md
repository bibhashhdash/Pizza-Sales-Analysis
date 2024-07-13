# Pizza-Sales-Analysis-

## Project Overview

Pizza Sales Analysis is an Exploratory Data Analysis project that is created by implementing SQL queries. It aims to gain insights into various aspects of pizza sales. This includes understanding sales trends over time, identifying the most popular types of pizzas, analyzing customer preferences, and uncovering patterns in sales data.

## Data Sources

1. pizzas.csv
2. pizza_types.csv
3. orders.csv
4. order_details.csv

## Tools

- SQL - DDL Commands, DML Commands, Aggregate Functions, Joins, Group By, Order By, Subqueries, Limit, etc.
- SQL Workbench - It is used to visualize the results.

## Exploratory Data Analysis

EDA involves exploring the datasets to answer questions like:

- Retrieve the total number of orders placed.
- Calculate the total revenue generated from pizza sales.
- Identify the highest-priced pizza.
- Identify the most common pizza size ordered.
- List the top 5 most ordered pizza types along with their quantities.
- Join the necessary tables to find the total quantity of each pizza category ordered.
- Determine the distribution of orders by hour of the day.
- Join relevant tables to find the category-wise distribution of pizzas.
- Group the orders by date and calculate the average number of pizzas ordered per day.
- Determine the top 3 most ordered pizza types based on revenue.
- Calculate the percentage contribution of each pizza type to total revenue.

## Results 

- Retrieve the total number of orders placed

  SELECT COUNT(order_id) AS total_orders FROM orders;

  <img width="74" alt="image" src="https://github.com/user-attachments/assets/101fb8a6-137a-44d6-8bc2-9985e8d67ef0">

  
