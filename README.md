# Practice-SQL

A place to practice my SQL syntax and logic 
Questions generated from ChatGPT

## Q1: Cohort Retention

You have a table orders:

user_id
order_id
order_date

Task:
Compute 30-day retention: for each user, did they place another order within 30 days of their first order? Return:

user_id | first_order_date | retained_within_30_days (true/false)
