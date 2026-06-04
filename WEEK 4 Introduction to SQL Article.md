# My First Time With SQL
## Introduction
This week was my first time learning and working with SQL. It was first a little difficult and confusing, especially when attempting to figure out how different commands interact. However, as I kept practicing and creating basic queries, I began to realize that SQL is, in fact, a simple and understandable language. Its power is what makes it even better; with just a few commands, you can build tables, add data, change it, and even filter precisely what you want to view. My confidence grew as I continued to practice and I also came to understand that mastering SQL takes patience and consistent practice. It gets much simpler to understand and apply efficiently with time and consistency. In this article, we are going to cover some of the SQL concepts that I found interesting such as Data Definition Language and Data Manipulation Language.

## Data Definition Language (DDL)
DDL, which stands for Data Definition Language, is used to create and manage the structure of a database. It focuses on the structure of the database, including establishing data types, defining columns, and constructing tables. In my instance, I used DBeaver to develop and execute my SQL queries while working with PostgreSQL as the database system.

One of the main commands in DDL is CREATE, which is used to create new tables. For example, when starting my assignment, I used the CREATE TABLE command to define a students table with columns such as student_id, first_name, and last_name as seen in the image below.
DDL is highly important because before you can store or manipulate any data, you first need to define the structure where that data will live.

## Data Manipulation Language (DML)
Another essential concept in SQL is Data Manipulation Language or DML.  DML is all about adding, modifying, removing, and retrieving the data inside tables within databases.

As seen in the screenshots below, INSERT, UPDATE, and DELETE are a few of the primary DML commands I used in my first SQL assignment. I was able to add new records, including names and the data that went with them, to my students table using the INSERT command and to change existing data using the UPDATE command, such as giving students. Additionally, I deleted entries that were no longer required using the DELETE command.

## The WHERE Clause
The WHERE clause is one of the most useful SQL concepts I've learnt. It is used to filter data so that only entries that satisfy certain criteria are returned. WHERE helps you concentrate on precisely what you are searching for rather than examining all the data in a table. Because of this, it is a crucial tool that is utilized in practically all SQL projects.

In order to identify exact matches, such students who reside in Nairobi, the WHERE clause sets conditions using several operators, such as the = operator. You may locate values greater than a specific quantity, like as students older than 18, by using the > operator. When dealing with ranges, such ages between 18 and 25, the BETWEEN operator is helpful. 

## CASE WHEN
The most challenging component for me this week was the CASE WHEN, but after practicing and watching video tutorials, I eventually gained basic knowledge of how it operates. I understood that it is used to apply conditions in SQL and return various outcomes based on those criteria.

At first, it was not very clear how to structure the CASE WHEN properly, and I kept getting confused about where each condition goes, but after examining other examples and attempting it myself, I gradually began to get it. I came to see how helpful it is for grouping data. 

## Key Takeaway This Week
As mentioned earlier, this week was my first time interacting with SQL, and this is because I hardly knew how important it is. After researching further on it, one key point I came across was a quote by Alice Zhao in her book SQL Pocket Guide where she writes "If there was a programming language award for best supporting actor, SQL would take home the prize", and this made me see the importance of SQL as a language not only for data specialists, but the tech world in general.