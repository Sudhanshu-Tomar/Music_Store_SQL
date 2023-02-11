# Music_Store_Analyis (Using SQL)
Tools : PostgreSQL 15 



![7-Pexels](https://user-images.githubusercontent.com/119277783/218251864-85310229-6da5-45e4-ac24-769803d6e0f3.jpg)


Introduction 

Music Emporium is a new music store opened by King, a passionate music lover. King has a deep love for all types of music, but his favorite genres are Rock, Pop, and Jazz. The store offers a wide range of musical instruments and accessories, as well as a collection of CDs and vinyl records.

Music Emporium is in need of your assistance to help the store thrive. Despite its popularity among music enthusiasts, the store has faced several challenges in its first few months of operation. The store has captured some basic data about its customers and sales,etc  but has no idea how to use this information to make informed business decisions.

The goal of this project is to help  Music Emporium make sense of its data and turn its passion for music into a successful business.



# Entity Relationship (ERD) Diagram 


![MusicDatabaseSchema](https://user-images.githubusercontent.com/119277783/218251449-d684d678-3af6-484a-934c-d364a1502b36.png)


 # Problem Statement
 
 The music store wants to analyze its customer and sales data to better understand its customer behavior and market trends. 
 The goal of the project is to answer various business questions related to customer behavior, sales, and music genres.
 
 
 ![883e4eeb283c668482a9f57d49ca5202](https://user-images.githubusercontent.com/119277783/218251976-d6a55197-1a5d-4a3d-ac22-c1af464617cc.gif)

 
 
-- MODULE 1 :

     Q1: Who is the senior most employee based on job title? 
  
     Q2: Which countries have the maximum Invoices?
  
     Q3: What are top 3 values of total invoice?

     Q4: Which city has the best customers? We would like to throw a promotional Music Festival in the city we made the most money. 
         Write a query that returns one city that has the highest sum of invoice totals. Return both the city name & sum of all invoice totals 

     Q5: Who is the best customer? The customer who has spent the most money will be declared the best customer. 
         Write a query that returns the person who has spent the most money.
         
         
         

![guitar-gif-1](https://user-images.githubusercontent.com/119277783/218252070-2ad3f081-df44-48d4-99f7-083cab8a9857.gif)




-- MODULE 2 :
     
     Q1: Write query to return the email, first name, last name, & Genre of all Rock Music listeners. Return your list ordered alphabetically by email starting with A.

     Q2: Let's invite the artists who have written the most rock music in our dataset. Write a query that returns the Artist name and total track count of the 
          top 10 rock bands. 

     Q3: Return all the track names that have a song length longer than the average song length. Return the Name and Milliseconds for each track.
         Order by the song length with the longest songs listed first.
         
         

![3450_gonzales_la](https://user-images.githubusercontent.com/119277783/218252139-dd853260-ed07-419d-ab3a-cd4920a81089.jpg)



-- MODULE 3 :

     Q1: Find how much amount spent by each customer on artists? Write a query to return customer name, artist name and total spent

     Q2: We want to find out the most popular music Genre for each country. We determine the most popular genre as the genre with the highest amount of purchases. 
         Write a query that returns each country along with the top Genre. For countries where the maximum number of purchases is shared return all Genres.

     Q3: Write a query that determines the customer that has spent the most on music for each country. 
         Write a query that returns the country along with the top customer and how much they spent. For countries where the top amount spent is shared, 
         provide all customers who spent this amount.
         
         
The music store wants to use this information to make informed decisions about promotional activities, customer engagement, and product offerings.    





![emojilaugh-emoji](https://user-images.githubusercontent.com/119277783/218252210-3e90903b-98f4-4630-8be6-a9fb25c7b256.gif)

