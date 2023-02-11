# Music_Store_Analyis (Using SQL)
Tools : PostgreSQL 15 





Entity Relationship (ERD) Diagram 


![MusicDatabaseSchema](https://user-images.githubusercontent.com/119277783/218251449-d684d678-3af6-484a-934c-d364a1502b36.png)


 # Problem Statement
 
 The music store wants to analyze its customer and sales data to better understand its customer behavior and market trends. The goal of the project is to answer various business questions related to customer behavior, sales, and music genres.
 
 
-- MODULE 1 :

     Q1: Who is the senior most employee based on job title? 
  
     Q2: Which countries have the maximum Invoices?
  
     Q3: What are top 3 values of total invoice?

     Q4: Which city has the best customers? We would like to throw a promotional Music Festival in the city we made the most money. 
         Write a query that returns one city that has the highest sum of invoice totals. Return both the city name & sum of all invoice totals 

     Q5: Who is the best customer? The customer who has spent the most money will be declared the best customer. 
         Write a query that returns the person who has spent the most money.


-- MODULE 2 :
     
     Q1: Write query to return the email, first name, last name, & Genre of all Rock Music listeners. Return your list ordered alphabetically by email starting with A.

     Q2: Let's invite the artists who have written the most rock music in our dataset. Write a query that returns the Artist name and total track count of the top 10 rock bands. 

     Q3: Return all the track names that have a song length longer than the average song length. Return the Name and Milliseconds for each track.
         Order by the song length with the longest songs listed first.


-- MODULE 3 :

     Q1: Find how much amount spent by each customer on artists? Write a query to return customer name, artist name and total spent

     Q2: We want to find out the most popular music Genre for each country. We determine the most popular genre as the genre with the highest amount of purchases. 
         Write a query that returns each country along with the top Genre. For countries where the maximum number of purchases is shared return all Genres.

     Q3: Write a query that determines the customer that has spent the most on music for each country. 
         Write a query that returns the country along with the top customer and how much they spent. For countries where the top amount spent is shared, 
         provide all customers who spent this amount.
