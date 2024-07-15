# Chapter 1


A database can simply be defined as a collection of related data.


## Data

Data is a set of facts that have implicit meaning. Examples include names, phone numbers, and addresses of people you may know.

### Data model

The data model of a DBMS refers to the abstraction layer over the actual stored data. For example, in the relational model, the user only needs to know the schema of the object they are storing, rather than how it will be stored in memory.


## Users

A User is the client of a database system. It can be a person writing queries, or an application program. Anything that 

### Views

A database typically has many users that it needs to serve data to. Some users may require access to different views of the data than others. A view may be a subset of the data, or even virtual data derived from the stored data.

For example, in a school database, administrators may need access to all student data, while students should only be given a view of their own data.

### Multi-user systems

DB Systems that allow for multiple users have many more edgecases than single user systems. Multiple users may try to access the database at the same time, so concurrency control software should be implemented to ensure that this is handled propperly.

The abstraction that many dbms systems have taken to solve this problem is a transaction. Transactions have some properties they should follow to correctly function in concurrent applications, such as isolation and atomicity. Transactions will be covered in a later chapter.

### Actors

The actors that typically have access to a production database include:

- Administrators
- Database Designers
- End users
- System analysts
- Application Programmers

## Advantages of DBMS approach

Using a DBMS holds many advantages over the traditional file system. 
