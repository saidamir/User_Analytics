# User_Analytics
# Goal

The   purpose   of   this   exercise   is   to   use   the sample   data   to   answer   some   typical questions   for   an  ecommerce   business   using   SQL. I have used the log files to recreate orders, revenues as well as cohorts data.

A set of CSVs that correspond to 4 different tables that represent fake order data for ~3.5M orders for across ~350K customers and 10 products over the course of almost 4 years.

This will not work in Excel, it will likely crash the program because it is too much data.

# Questions

created a chart showing the # of orders per month
created a chart showing revenue per month
created a table showing the retention rate by monthly cohort
created a table showing the subsequent period spend by monthly cohort

# Schema
The   following   relationships   exist   in   the   data   (foreign   keys   between   the   tables   should   be self-explanatory):
● An   order   has   many   order   line   items
● An   order   line   item   belongs   to   a   product
● A   product   has   one   stock   unit
● An   order   has   one   payment
● A   payment   can   have   a   refund

# Final work
Two charts in .png format
Two csv files containing tables
Three Jupiter Notebook files with the work.
I did all the work in Jupyter Notebooks using Python.
I also created SQL script to perform the same tasks.

![orders_by_month_year](https://user-images.githubusercontent.com/20246711/34623872-d871ab2c-f207-11e7-8a1b-c244190d4eaa.png)

![revenue_by_month](https://user-images.githubusercontent.com/20246711/34624029-849a4fa8-f208-11e7-9759-a399f6d61eb4.png)
