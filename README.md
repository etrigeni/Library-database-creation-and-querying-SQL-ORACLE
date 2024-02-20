# Library-database-creation-and-querying

Database Description:

1. The university’s library called DIPLIB wants to commission a database for recording their books, the authors, the users, and the loans.
2. The library has many books. Details like ISBN, title, author, genre, edition, number of pages, publication date, price, etc. are recorded.
3. Each book has an author. For simplicity, only the first author will be documented and not the co-authors. For each author, an ID will be given and details such as last name, first name, date of birth, date of death (where applicable), country of origin, gender etc. should be recorded.
4. Each book may have several copies, but a copy can only be of one book. The copy has a unique ID. The only other details that is needed is the book’s ISBN and the date of purchase.
5. Only copies of the books may be loaned out, several times. For simplicity, a loan must be of a copy and only one copy per loan. A unique ID per loan must be assigned. Other details like, the user’s ID, the date of the load, the return date, are required.
6. The library stores information about their users. Users are not entered on the system unless they have taken out a copy of a books. The users can have several loans, a loan must be assigned to a user. User details like last name, first name, email, contact details, gender, etc. are recorded.
