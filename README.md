🍽️ Restaurant Orders Analysis

This project contains SQL scripts to explore and analyze a restaurant database (restaurant_db). The database includes information about menu items and order details, allowing insights into pricing, categories, and customer spending behavior.

📂 Project Structure

menu_items.sql → Queries to explore the menu, categories, and pricing.


order_details.sql → Queries to analyze orders, date ranges, and item counts.


Combined analysis.sql → Queries combining both tables to study spending patterns and popular items.


🔍 Key Queries


Menu Items



View the menu_items table:


Find the number of items on the menu:

<img width="307" height="42" alt="image" src="https://github.com/user-attachments/assets/1d57b96f-395d-4609-8bdd-6ccb82e5ab2f" />


Find the least and most expensive items on the menu:

<img width="347" height="53" alt="image" src="https://github.com/user-attachments/assets/d7ac167c-feac-46e8-9596-c40b7eb53b43" />


Count how many Italian dishes are on the menu:

<img width="384" height="62" alt="image" src="https://github.com/user-attachments/assets/32898750-c89e-4b04-a562-3c84eea7c505" />


Find the least and most expensive Italian dishes:

<img width="338" height="80" alt="image" src="https://github.com/user-attachments/assets/74ab8e50-5cb7-4dbd-b71f-0a1811e51272" />


Count how many dishes are in each category:

<img width="491" height="81" alt="image" src="https://github.com/user-attachments/assets/cea08b96-865d-4345-84ad-e21b205288a0" />


Find the average dish price within each category:

<img width="402" height="82" alt="image" src="https://github.com/user-attachments/assets/f6ddc2b6-39a8-46d6-bdfc-8788442ce66c" />


Order Details

View the order_details table:

<img width="337" height="53" alt="image" src="https://github.com/user-attachments/assets/b3e94f1f-7a93-419f-b922-6b65a5108c8d" />


Find the date range of the table:

<img width="515" height="52" alt="image" src="https://github.com/user-attachments/assets/183cd386-c094-463a-a8a1-1803ade6da60" />


Count how many orders were made within this date range:

<img width="451" height="49" alt="image" src="https://github.com/user-attachments/assets/cb357ac6-c30a-47ae-9aab-04fec8c47a9d" />


Count how many items were ordered within this date range:

<img width="375" height="45" alt="image" src="https://github.com/user-attachments/assets/008a6c7c-3573-4f90-a609-cd475d43b49a" />


Find which orders had the most number of items:


<img width="445" height="85" alt="image" src="https://github.com/user-attachments/assets/2c1dd632-86ef-4118-8e6f-a8b6f9ae7e23" />


Count how many orders had more than 12 items:

<img width="489" height="151" alt="image" src="https://github.com/user-attachments/assets/418ef63c-0623-4511-83be-cfa311b65c7a" />


Combined Analysis:



Combine the menu_items and order_details tables into a single table:

<img width="507" height="132" alt="image" src="https://github.com/user-attachments/assets/0ec1020e-ff49-4de5-a14a-397aad564bd8" />


Find the least and most ordered items, and their categories:

<img width="584" height="117" alt="image" src="https://github.com/user-attachments/assets/803df410-9d99-48b8-aed1-68d9fa44d030" />


Find the top 5 orders that spent the most money:

<img width="521" height="136" alt="image" src="https://github.com/user-attachments/assets/324d62a7-d996-47c3-9ac7-a92a65a1d672" />


View the details of the highest-spending order:

<img width="533" height="115" alt="image" src="https://github.com/user-attachments/assets/20976e8d-333c-4bd5-8389-59cda61a71ca" />


View the details of the top 5 highest-spending orders:

<img width="557" height="157" alt="image" src="https://github.com/user-attachments/assets/0cf34e06-07d5-4774-937d-4ed1a6cf7cef" />



Insights


Identified the least and most expensive dishes.


Calculated average prices per category.


Analyzed order volumes and item counts.


Found the top 5 orders with the highest spending.


Discovered which categories dominate in high-value orders.


How to Run


Open MySQL Workbench (or any SQL client).


Connect to your database and select the schema restaurant_db.


Run the scripts (menu_items.sql, order_details.sql, Combined analysis.sql).


Review the results and insights.





