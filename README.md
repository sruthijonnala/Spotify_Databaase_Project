# Spotify_Databaase_Project

This project features a collection of SQL queries crafted to extract distinct insights from a simulated
Spotify database.
### Purpose
The Spotify SQL Project uses SQL queries to explore and understand a typical music store’s data. The
queries aim to answer important questions about Spotify’s operations, customer habits, and sales,
offering useful insights that can help improve the business and increase profits.
### Data
The data is stored in several tables within the database. Based on the queries, some of the tables
include employee, invoice, customer, invoice_line, track, genre, artist, and album.
### Analysis Approach:
The project is segmented into three tiers of complexity: Easy, Moderate, and Advanced.
 Easy Level: Features basic queries that focus on direct data retrieval, such as pinpointing top
customers or employees.
 Moderate Level: Encompasses intermediate queries that dig deeper, using complex JOIN
operations, GROUP BY clauses, and aggregate functions like SUM and COUNT to derive more
nuanced insights.
 Advanced Level: Showcases the power of advanced SQL techniques. It prominently uses
Common Table Expressions (CTEs) and window functions like ROW_NUMBER to answer
complex queries.
#### SQL Constructs Used:
The project uses a wide range of SQL constructs to address various querying needs:
 Data Retrieval: SELECT, DISTINCT, and FROM.
 Filtering: WHERE, IN, and LIMIT.
 Aggregation: SUM, COUNT, AVG.
 Sorting: ORDER BY.
 Joining Tables: JOIN.
 Grouping Data: GROUP BY.
 Window Functions: ROW_NUMBER.
 Subqueries and Derived Tables: WITH (for CTEs)

## Questions
### Easy Level Questions:
1. Who is the senior most employee based on job title?
2. Which countries have the most Invoices?
3. What are top 3 values of total invoice?
4. Which city has the best customers? We would like to throw a promotional Music.
5. Who is the best customer? The customer who has spent the most money will be declared the best
customer. Write a query that returns the person who has spent the most money.
### Moderate Level Questions:
1. Write query to return the email, first name, last name, &amp; Genre of all Rock Music listeners. Return
your list ordered alphabetically by email starting with A.
2. Let&#39;s invite the artists who have written the most rock music in our dataset. Write a query that
returns the Artist name and total track count of the top 10 rock bands.
3. Return all the track names that have a song length longer than the average song length. Return
the Name and Milliseconds for each track. Order by the song length with the longest songs listed
first.
### Advance Level Questions:
1. Find how much amount spent by each customer on artists? Write a query to return customer
name, artist name and total spent.
2. We want to find out the most popular music Genre for each country. We determine the most
popular genre as the genre with the highest amount of purchases. Write a query that returns each
country along with the top Genre. For countries where the maximum number of purchases is shared
return all Genres.
3. Write a query that determines the customer that has spent the most on music for each country.
Write a query that returns the country along with the top customer and how much they spent. For
countries where the top amount spent is shared, provide all customers who spent this amount.
