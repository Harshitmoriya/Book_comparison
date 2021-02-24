# Purpose:

   We are going to make a Book price comparison website in which we can find a price of a particular book in various different E-commerce stores such as amazon,flipkart etc,
so that people can buy books according to their budget.

# How I am going to do this:

  Firstly we are going to design a wireframe which contains a basic content of our website.After that we are going to make database for storing user input and for connecting databse to ou
website we use REST api. We are going to use pyhton

# Database Schema design:

## Following is my schema design-
 1. > Book_Details (Book_ID, Book_Name, Release_date, Publications, Rating)  
Here **Book_ID** act as our primary key.

 2. There is possibilities that one book may have been printed by more than one author, so for that scenario we are going to make a new schema name as **Authors**.  
> Authors(Book_ID,Author)

 3. A certain book/novel is available on different E-commerce on different prices, so for that we are making a seperate schema named as **Sites**.  
> Sites(Book_ID,Available_on,Book_price)

## Assumptions:
* One book may be published by many publishers so for that scenario the book published by each publishers which have been given a seperate Book_ID.








