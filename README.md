# elevate-lab-SQL-Task-4
This repository contains my hands-on work with SQLite during my ELEVATE LAB INTERNSHIP
# Task 4: Aggregate Functions and Grouping

## What I Did:
In this task, I worked with a hotel management system database and learned how to use aggregate functions in SQL. I created a new table called `payments` to make the data more realistic and relevant to work with. Then I explored how to analyze and summarize the data using functions like sum, average, and count.

## Tools I Used:
- MySQL Workbench to run and test queries


## What Kind of Work I Did:
- I added a `payments` table that connects to the `guests` table using `guest_id`
- I added sample payment data for different guests
- I used functions like total payment, average payment, and number of payments
- I grouped data by guest to see per-guest summaries
- I filtered results using `HAVING` to show only guests with totals above certain amounts

## What I Learned:
- Aggregate functions are used to summarize data (like total or average)
- `GROUP BY` is used when we want results per group (like per guest or city)
- `HAVING` is used to filter grouped data, while `WHERE` is used before grouping
- Filtering groups helps to find meaningful insights (like who paid the most)


Deliverables:
- A complete working `payments` table with test data
- Practical understanding of aggregate functions and grouping in SQL
- A set of tested queries (not shown here) that summarize and filter data
- This README file that explains what I did in my own words
