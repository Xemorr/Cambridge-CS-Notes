# Databases
Databases is one of the first courses taken in Computer Science at Cambridge.

## What is a database management system? (DBMS)
Database management interfaces are often very large when programming, as they often include querying languages. 

Databases use [[CRUD]] and [[ACID]] transactions, the fact that they use ACID transactions is what makes an operating system's file system not be thought of as a database. [[ACID]] is particularly useful when allowing for numerous concurrent users. 

There are two common categorisation of databases [[NoSQL]] and [[SQL]]. Although, both of these databases often steal ideas from the other side. 

## Databases focuses on three specific data models
### [[Relational Model]]
 Data is stored in tables (SQL).
 
### [[Aggregate-oriented Model]]
Document Oriented Database, optimised for read speeds, worse for writing.

### [[Graph-oriented Model]] 
The data is stored as a graph. Query languages have to think in terms of paths.

## The three database systems used

### HyperSQL
A Java-based relational database management system using traditional SQL.

### DOCtor Who
A bespoke document-oriented collection of data, it isn't really a database management system, it is really just some python dictionaries behaving like a DBMS!

### Neo4j
A graph-oriented java database management system. This languages used [[Cypher]] for querying.