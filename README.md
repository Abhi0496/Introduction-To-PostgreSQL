## Introduction To PostgreSQL

This repo contains my notes/Codes from the LinkedIn learning course- Introduction to PostgreSQL

Chapter 1) Introducing PostgreSQL
    * What is PostgreSQL?
        It's a object-relational, open-source database management system that is performant, reliable, and secure, no matter where you choose to deploy. It's based on relational structure, it has some object-oriented programming features such as classes inheritance and polymorphism. It can also handle NoSQL functionality. JSON and JSON-B data types
    
    * Key features-
        **Extends SQL
        **Functions and procedures can be written in other language-> C, C++, .NET, PL/PgSQL, PL/Python, PL/JAVA
        **ACID compliant-> For each transaction Postgres ensures Atomicity, Consistency, Isolation and Durability. ACID compliance helps to maintain the integrity of data
        ** Multi Version Concurrency Conttrol(MVCC) which provides concurrent access to database without read blocking so that readers do not block writers and vice versa. User does not see any changes in data unlss the transaction in committed. The row and page are both still readable by other users even while changes are being mage
        ** B Tree is default index used in Postgres
        ** It supports creation of views, triggers, stored procedures
        ** P SQL is default command line client, GUI extensions like PF Admin

    * ORDBMS- Object Relational Database Management System
        Database are either relational or Non relational
        | Relational | Non-Relational |
        | ---------- | ---------- |
        | Standardized | Non-Standardized | 
        | Vertically Scalable | Horizontally Scalable| 
        | Fixed Schema | Dynamic Schema | 
        | ACID | BASE |
        | Efficient and reliable to handle complex code | Simple and flixible to handle significant changes but inefficient to handle complex code |
    
    Note- Over the time changes have been made and Postgres is horizontally scalable with logical replication and container infrastructure

    * Summary-
        ** Relational at its core (ORDBMS)
        ** SQL Compliant
        ** Inherently vertically scalable
        ** Horizonta scalable using logical replication cotainers or other solutions
        ** Designed to support many data types- JSON/JSON B, XML, Key-Value, Geometric
