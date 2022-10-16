# Reading Notes for Day 4 of 401:

## nosql vs sql

- What type of database is the best fit for the complex query intensive environment? 
nosql
- What type of database is the best fit for hierarchical data storage?
SQL
- Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.
They're both scalable, but SQL databases are better when you have clear relationships and noSQL databases are bettere when you might want to add random unplanned information. 

## sql modeling techniques

- Among data tables, what is a one-to-many relationship and how do we “relate” them? 
One to many means on one side you will only have one, and on the other you will have many. Like a book might have many pages, but a page wouldn't have many books.

- Prior to designing your relational database, it might be useful to make a map of the database tables and their relationships.

- Explain the difference between a primary and foreign key. 

A primary key is the unique key related to that record and a foreign key is the unique identifier of another record, usually from another table.

## Videos

## sql vs nosql

- How do we treat keywords and parameters differently in SQL syntax? 



- Define normalization within the context of schemas and data.

Normalization is how you organize the data within a database and a database schema is the blueprint for that normalization.

- Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter. 

A one to many relationship is like books and pages, a book has many pages, but a page only exists within one book. A many to many relationship is like books and bookstores, a book can be in many bookstores, and many bookstores can carry a particular book.


Bookmark and Review
sequelize api


### Things I want to know more about:

[back to Table of Contents](./README.md)
