# PizzaHut-Sales-SQL
I have developed this project to analyze pizza sales for a store, providing insights by addressing key <a href="https://github.com/HemangTaori/PizzaHut-Sales-SQL/blob/main/questions.txt">Questions</a> that assist the café owner in making informed business decisions.

## Files Used:
<li><a href="https://github.com/HemangTaori/PizzaHut-Sales-SQL/blob/main/order_details.csv">order_details</a></li>
<li><a href="https://github.com/HemangTaori/PizzaHut-Sales-SQL/blob/main/orders.csv">orders</a></li>
<li><a href="https://github.com/HemangTaori/PizzaHut-Sales-SQL/blob/main/pizza_types.csv">pizza_types</a></li>
<li><a href="https://github.com/HemangTaori/PizzaHut-Sales-SQL/blob/main/pizzas.csv">pizzas</a></li>

## Technology Used
<li> MySQL</li>
<li> Excel</li>

## Overview
This project utilizes four CSV files to manage and analyze pizza orders efficiently. The order_details table contains four columns: order_details_id, order_id, pizza_id, and quantity, which represents the number of pizzas ordered. The orders table consists of three columns: order_id, which serves as the primary key for tracking orders, order_date, which records the date an order was placed, and order_time, which logs the exact time of the order. These tables help maintain a structured record of customer purchases, enabling effective order management and tracking.

The pizza_types table provides detailed information about different pizza varieties, containing four columns: pizza_type_id, which uniquely identifies each pizza type, name, which specifies the name of the pizza, category, which classifies pizzas into groups such as classic, vegetarian, or chicken-based, and ingredients, which lists the components used in each pizza. The pizzas table further complements this by storing pizza_id, which links to the orders table, pizza_type_id, which connects to the pizza_types table, size, which indicates available pizza sizes (e.g., small, medium, large, extra-large), and price, which represents the cost of each pizza. Together, these tables form a comprehensive dataset that supports order processing, pricing analysis, and customer preference tracking.

## Result
The answers to the questions asked are shown <a href="https://github.com/HemangTaori/PizzaHut-Sales-SQL/blob/main/Pizza_Sales.pdf">here.</a>
