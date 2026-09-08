Olist E-commerce Sales Analysis (SQL)

Analyzed 100K+ orders from Olist, a Brazilian e-commerce marketplace, to answer 
practical business questions around revenue, customers, and delivery performance 
using MySQL.

Why this project
Coming from a commerce background, I wanted to apply SQL to a dataset that 
mirrors real retail/e-commerce operations not just textbook queries, but 
questions a business team would actually ask.

Dataset
Public Olist dataset (Kaggle) 6 relational tables covering customers, orders, 
order items, products, payments, and reviews.

Business Questions Answered
- How is revenue trending month over month, and what's the growth rate?
- Which product categories bring in the most revenue vs. the most orders?
- Who are our best customers, based on how recently, how often, and how much 
  they buy (RFM analysis)?
- What percentage of customers come back for a second order?
- Which states generate the most sales, and how does that line up with 
  delivery delays?
- How do customers prefer to pay, and how does that vary?
- Which product categories get the best and worst reviews?

SQL techniques used
CTEs, window functions (NTILE, LAG, SUM OVER), multi-table joins, 
GROUP BY/HAVING, date-based aggregations

What I found
- Health & Beauty and Watches & Gifts drive the highest revenue, but 
  Bed/Bath/Table has the highest order volume, different categories win 
  on different metrics.
- Repeat purchase rate is low, which is typical for Olist as a marketplace 
  rather than a single-brand store.
- Delivery delays vary meaningfully by state, which could inform logistics 
  decisions.
