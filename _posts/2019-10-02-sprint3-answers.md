---
layout: post
title: Blog Post on MongoDB and NewSQL
subtitle: small post on sql databases

---


### Answers to the Sprint Questions on 11th Oct 2019

### Relationship between Employee and Territory tables in the Northwind database  


Each Territory is associated with an Employee Id  
Each Employee is associated with multiple territories  
Relation between Employee and Territories table is One to Many relationship  


### MongoDB - when to use and not

MongoDB is a object oriented NOSQL database.  

#### MongoDB puts focus on flexibility
#### MongoDB puts focus on availability first
#### MongoDB is good for alternative data models or for special use cases

It should be used when most of the data to be stored is of document types such as Json, HTML or other objects.  
Sometimes when the data of an application is humungous MongoDB can be considered.  
MongoDB is an appropriate choice when Performance and Availability are of high importance for the database.  
  
  
When consistency of the data is critical and also ACID compliance (Atomic, Consistency, Isolation, Durability) is of utmost priority, than MongoDB is not the appropriate choice.  
That is when Correctness and Consistency are of High Importance for database MongoDB should not be used.  


### NewSQL - 

NewSQL is a new approach to the Relational Databases which is trying to provide the advantages of 
ACID (atomicity, consistency, isolation, durability) of Relational Databases along with advantages
of the horizontal scalability of NoSQL databases such as MongoDB

#### THE NEWSQL ADVANTAGES:

Minimize application complexity stronger consistency and often full transactional support.
Familiar SQL and standard tooling.
Richer analytics leveraging SQL and extensions.
Many systems offer NoSQL-style clustering with more traditional data and query models.

#### THE NEWSQL DISADVANTAGES:

No NewSQL systems are as general-purpose as traditional SQL systems set out to be.
In-memory architectures may be inappropriate for volumes exceeding a few terabytes.
Offers only partial access to the rich tooling of traditional SQL systems.
