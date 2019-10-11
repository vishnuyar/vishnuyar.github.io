---
layout: post
title: Blog Post on MongoDB and NewSQL
subtitle: small post on sql databases

---


## Answers to the Sprint Questions on 11th Oct 2019

### Relationship between Employee and Territory tables in the Northwind database 

Each Territory is associated with an Employee Id
Each Employee is associated with multiple territories
Relation between Employee and Territories table is One to Many relationship


### MongoDB - when to use and not

MongoDB is a object oriented NOSQL database, It should be used when most of the data
to be stored is of document types such as Json, HTML or other objects. Sometimes when the data
of an application is humungous and at the same time availability of the data is more important
than the latest data, MongoDB is an appropriate choice that is when Performance and Availability
are of high importance for the database then MongoDB should be used.


When consistency of the data is critical and also ACID compliance (Atomic, Consistency, Isolation, Durability) is of utmost priority for the database than MongoDB is not the appropriate choice.
that is Correctness and Consistency are of High Importance for database MongoDB should not be used

### NewSQL - 

NewSQL is a new approach to the Relational Databases which is trying to provide the advantages of 
ACID (atomicity, consistency, isolation, durability) of Relational Databases along with advantages
of the horizontal scalability of NoSQL databases such as MongoDB
