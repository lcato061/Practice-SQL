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

## Q2: Monthly Active Users (MAU) by Cohort

You have a table events:

user_id
event_date
event_type

Task:
For each signup month (assume first event_type = 'signup' is signup date), compute number of active users per month for the first 3 months.

Output:

signup_month | month | active_users

Tip: Use CTEs and DATE_TRUNC('month', ...).
