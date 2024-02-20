# Library-database-creation-and-querying

The project conducted in the context of the databases course. The aim was to create and querying a database for a library.

**Database Description**:

1. The university’s library called DIPLIB wants to commission a database for recording their books, the authors, the users, and the loans.
2. The library has many books. Details like ISBN, title, author, genre, edition, number of pages, publication date, price, etc. are recorded.
3. Each book has an author. For simplicity, only the first author will be documented and not the co-authors. For each author, an ID will be given and details such as last name, first name, date of birth, date of death (where applicable), country of origin, gender etc. should be recorded.
4. Each book may have several copies, but a copy can only be of one book. The copy has a unique ID. The only other details that is needed is the book’s ISBN and the date of purchase.
5. Only copies of the books may be loaned out, several times. For simplicity, a loan must be of a copy and only one copy per loan. A unique ID per loan must be assigned. Other details like, the user’s ID, the date of the load, the return date, are required.
6. The library stores information about their users. Users are not entered on the system unless they have taken out a copy of a books. The users can have several loans, a loan must be assigned to a user. User details like last name, first name, email, contact details, gender, etc. are recorded.


**OBJECTIVES**:
Task 1: Table Specifications
Create a table (there is an example in Appendix A) with the database specifications based on the given Entity Relationship Diagram (ERD). You should consider the following:
• appropriate table name, datatypes, constraints and defaults
• integrity
• case

Task 2: Script Files
Use the ERD and your table specifications to create the following script files (all files should have an appropriate extension with proper details, run commands and comments).


**1. create_yourTwoSurnames.txt**
▪ Create table commands for all tables
ADVANCED DATABASE SYSTEM ~ 2 ~ GROUP ASSIGNMENT
▪ Tables should be created in the correct order to maintain integrity
▪ Include:
o NULL constraints and defaults
o Sequences


**2. constraint_ yourTwoSurnames.txt**
▪ Alter table… add constraint commands for all tables (primary keys, foreign keys, unique, checks)
▪ Constraints should be created in the correct order to maintain integrity and named after the instructions on your lad notes
▪ Any changes to the attributes you consider important (add new attributes, defaults, upper, change attributes, etc.)



**3. insert_ yourTwoSurnames.txt**
▪ Insert commands for all tables
▪ Regarding the number of entries per table, do not overload the database
▪ Inserts should be in the correct order to maintain integrity
▪ Data should be appropriate to support queries in task 2.5
▪ Use two different methods for inserts (with or without the column list, be careful when you have used DEFAULT)


**4. drop_ yourTwoSurnames.txt**
▪ Drop table, constraints and sequences
▪ Drops should be in the correct order to maintain integrity (do not just drop the table)
▪ Any additional commands you consider important


**5. query_ yourTwoSurnames.txt**
▪ Queries to achieve the following data:


a) All the records from one table

b) A projection with 3 columns

o data returned sorted in reverse alphabetical order

c) Restriction queries with multiple clauses demonstrating the following
o E.g. the authors of a specific genre
o a condition matching a pattern e.g. begins with J, ends with SON.
o a negative condition predicate e.g. are not from Greece
o a date range condition e.g. last year April - September

d) Join queries with data from
o 2 tables
o 3 tables
o More tables

e) Aggregate functions
1. Show the authors that their surname starts with K and ends with G.
2. Show the total number of books per genre.
3. Which book was the most popular (was loaned the most times) each year?
4. Show the authors in an ascending order and the books they wrote.
5. How many books were written in 1981?
6. Show the authors that have written “SCI-FI” or “HORROR” books
7. Show the titles of the books that were loaned in October (regardless the year).
8. How many alive and how many dead authors exist in the database?
9. Show the author who lived the longest
10. Show the author who currently is the oldest
11. Show the authors and the total number of books they have written.
12. Show the authors that none of their books was loaned.
13. Show the books that never were loaned by any user

    
**ADVANCED DATABASE SYSTEM ~ 3 ~ GROUP ASSIGNMENT**
15. Show the total worth of the books (total price) per year they were published.
16. Show the total worth of the books (total price) for the female and the male authors.
17. Show the book with the most copies in the library.
18. Show the authors who are not from “ENGLAND”.
19. Which users loaned the book titled “BLUES FOR A BLACK CAT”?
20. Show the authors in descending order of the average pages of their books.
21. Which English book is the most expensive?


**Extra query demonstrating additional or integrated skills**
1. Which user has read the most pages?
2. Which user has loaned the most books?
3. Show on average the number of books the female and the male users have loaned.
4. Assume a username for the users is made up of the first 3 letters of the first name added to the first 4 letters of the surname. Write the query to create and show the username for each user. Do not attempt to input it in the users table.
5. Assume that the return date of the book is 14 days after the loan date. Write the query to create and show the return date for each load. Do not attempt to input it in the loans table.
6. Which author has written the most pages in total?
7. Which genre has the most books?
8. Which year had the most total loans?
9. How many books were written by Greek authors?
10. Which books have the word “MISERY” in their title?
