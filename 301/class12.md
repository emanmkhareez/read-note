# Mongo and Mongoose


 ## five differences between SQL and NoSQL databases:

# SQL                                   NOSQL

 Relational Databases RDBMS            non-relational or distributed database 

 databases are table based databases   databases are document based, key-value pairs,
                                        graph databases or wide-column stores

have standard schema                    not have standard schema

predefined schema for structured data   dynamic schema for unstructured data.

vertically scalable                      horizontally scalable

structured query language                Unstructured Query Language

examples: MySql, Oracle, Sqlite,          examples: MongoDB, BigTable    
Postgres and MS-SQL

 good fit for the complex query         not good fit for complex queries.



                         
                                    


## What kind of data is a good fit for an SQL database? 

structured

## Give a real world example.

used by business professionals or program developers for administering, updating, maintaining and manipulating the databases or tables that are used for business decision-making.

## What kind of data is a good fit a NoSQL database?

 unstructured and unrelated data

## Give a real world example.

NoSQL is used for Big data and real-time web apps. 

### For example, companies like Twitter, Facebook and Google collect terabytes of user data every single day.

## Which type of database is best for hierarchical data storage?  NoSQL

as it follows the key-value pair way of storing data similar to JSON data

## Which type of database is best for scalability?

 In most typical situations, SQL databases are vertically scalable. You can manage increasing load by increasing the CPU, RAM, SSD, etc, on a single server.


NoSQL databases are horizontally scalable. You can just add few more servers easily in your NoSQL database infrastructure to handle the large traffic.





# PART2

## What does SQL stand for?

 Structured Query Language

## What is a realational database?

A relational database stores and organizes data points that are related to one another. Based on the relational database model, a relational database presents data sets as a collection of tables and provides relational operators to manipulate the data in tabular form.

  ![relational DB](https://assets-global.website-files.com/5debb9b4f88fbc3f702d579e/5e3c1a71724a38245aa43b02_99bf70d46cc247be878de9d3a88f0c44.png).

## What is a ‘schema’?

is an outline, diagram, or model. In computing, schemas are often used to describe the structure of different types of data. Two common examples include database and XML schemas.

This tells us about the structural view of the database. It gives us an overall description of the database. A database schema defines how the data is organised using the schema diagram

![ schema diagram](https://s3.ap-south-1.amazonaws.com/afteracademy-server-uploads/what-is-schema-diagram-b8915aa44db73ede.jpg).

There are three levels of the schema. The three levels of the database schema are defined according to the three levels of data abstraction.

View Schema

Logical Schema

Physical Schema

![ schema ](https://s3.ap-south-1.amazonaws.com/afteracademy-server-uploads/what-is-a-schema-three-levels-of-schema-84a896db453efdac.jpg).  


## What is a NoSQL database?

databases are flexible, scalable, and highly adaptable to the data management demands of modern businesses.

## Howo does it work?

every item in the DB stands on its own this simple modification means that they're essenntially key-value stores 

each item in the DB has only two fields a unique key and value 

value can be something like json document containg 
 
 if asingle DB server is not enough to store all your  data or handle all the queries 
 you can split the workload across two or more severs each server will then be responsible for only  part of your DB

## What is inside of a Mongo database?

 data objects are stored as separate documents inside a collection instead of in the traditional columns and rows of a relational database. The documents are stored as binary JSON or BSON objects.

## Which is more flexible - SQL or MongoDB? and why.


This is an easy one, and a hands down win for MongoDB. The schemaless design of MongoDB documents makes it extremely easy to build and enhance applications over time, without needing to run complex and expensive schema migration processes as you would with a relational database.

With MongoDB, there are more dynamic options for updating the schema of a collection, such as creating new fields based on an aggregation pipeline or updating nested array fields. This benefit is particularly important as databases grow in size. In contrast, larger MySQL databases are slower to migrate schemas and stored procedures that can be dependent on the updated schemas. MongoDB’s flexible design makes this much less of a concern.

## What is the disadvantage of a NoSQL database?

1-don’t have the reliability functions which Relational Databases have (basically don’t support ACID(Atomicity, Consistency, Isolation, and Durability).

2-In order to support ACID developers will have to implement their own code, making their systems more complex.

3-This may reduce the number of safe applications that commit transactions, for example bank systems.

4-are very new compared to Relational Databases, which means that are far less stable and may have a lot less functionalities.

![ NOSQL ](https://res.cloudinary.com/practicaldev/image/fetch/s--c5dHJonR--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_auto%2Cw_880/https://thepracticaldev.s3.amazonaws.com/i/h3qcpsvalz0mqqwnd7hk.png).  
