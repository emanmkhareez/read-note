***Data modeling ***'
is the process of creating a visual representation of either a whole information system or parts of it to communicate connections between data points and structures.

Data modeling makes it easier to integrate high-level business processes with data rules, data structures, and the technical implementation of your physical data. Data models provide synergy to how your business operates and how it uses data in a way that everyone can understand



**Jest**

 is a JavaScript testing framework designed to ensure correctness of any JavaScript codebase. It allows you to write tests with an approachable, familiar and feature-rich API that gives you results quickly


 **REST** 
 
 is acronym for REpresentational State Transfer. It is architectural style for distributed hypermedia systems

**this**

 Inside a function, the value of this depends on how the function is called.

In most cases, the value of this is determined by how a function is called (runtime binding). It can't be set by assignment during execution
The super keyword is used to access and call functions on an object's parent.

**super**
The super.prop and super[expr] expressions are valid in any method definition in both classes and object literals.

Syntax
super([arguments]); // calls the parent constructor.
super.functionOnParent([arguments]);


**data model**

 Data Model
The Data Model is defined as an abstract model that organizes data description, data semantics, and consistency constraints of data. The data model emphasizes on what data is needed and how it should be organized instead of what operations will be performed on data. Data Model is like an architect's building plan, which helps to build conceptual models and set a relationship between data items.


***data modeling***

Data modeling (data modelling) is the process of creating a data model for the data to be stored in a database. This data model is a conceptual representation of Data objects, the associations between different data objects, and the rules. Data modeling helps in the visual representation of data and enforces business rules, regulatory compliances, and government policies on the data. Data Models ensure consistency in naming conventions, default values, semantics, security while ensuring quality of the data.

Conceptual Data Model:

 This Data Model defines WHAT the system contains. This model is typically created by Business stakeholders and Data Architects. The purpose is to organize, scope and define business concepts and rules.

Logical Data Model
: Defines HOW the system should be implemented regardless of the DBMS. This model is typically created by Data Architects and Business Analysts. The purpose is to developed technical map of rules and data structures.

Physical Data Model:

 This Data Model describes HOW the system will be implemented using a specific DBMS system. This model is typically created by DBA and developers. The purpose is actual implementation of the database

# sql no sql
five differences between SQL and NoSQL databases:
SQL
Relational Databases RDBMS

databases are table based databases

have standard schema

predefined schema for structured data

vertically scalable

structured query language

examples: MySql, Oracle, Sqlite,
Postgres and MS-SQL

good fit for the complex query

NOSQL
non-relational or distributed database

databases are document based, key-value pairs, graph databases or wide-column stores

not have standard schema

dynamic schema for unstructured data.

horizontally scalable

Unstructured Query Language

examples: MongoDB, BigTable

not good fit for complex queries

What kind of data is a good fit for an SQL database?
structured

Give a real world example.
used by business professionals or program developers for administering, updating, maintaining and manipulating the databases or tables that are used for business decision-making.

What kind of data is a good fit a NoSQL database?
unstructured and unrelated data

Give a real world example.
NoSQL is used for Big data and real-time web apps.

For example, companies like Twitter, Facebook and Google collect terabytes of user data every single day.
Which type of database is best for hierarchical data storage? NoSQL
as it follows the key-value pair way of storing data similar to JSON data

Which type of database is best for scalability?
In most typical situations, SQL databases are vertically scalable. You can manage increasing load by increasing the CPU, RAM, SSD, etc, on a single server.

NoSQL databases are horizontally scalable. You can just add few more servers easily in your NoSQL database infrastructure to handle the large traffic.

PART2
What does SQL stand for?
Structured Query Language

What is a realational database?
A relational database stores and organizes data points that are related to one another. Based on the relational database model, a relational database presents data sets as a collection of tables and provides relational operators to manipulate the data in tabular form.

relational DB.

What is a ‘schema’?
is an outline, diagram, or model. In computing, schemas are often used to describe the structure of different types of data. Two common examples include database and XML schemas.

This tells us about the structural view of the database. It gives us an overall description of the database. A database schema defines how the data is organised using the schema diagram

 schema diagram.

There are three levels of the schema. The three levels of the database schema are defined according to the three levels of data abstraction.

View Schema

Logical Schema

Physical Schema

 schema .

What is a NoSQL database?
databases are flexible, scalable, and highly adaptable to the data management demands of modern businesses.

Howo does it work?
every item in the DB stands on its own this simple modification means that they're essenntially key-value stores

each item in the DB has only two fields a unique key and value

value can be something like json document containg

if asingle DB server is not enough to store all your data or handle all the queries you can split the workload across two or more severs each server will then be responsible for only part of your DB

What is inside of a Mongo database?
data objects are stored as separate documents inside a collection instead of in the traditional columns and rows of a relational database. The documents are stored as binary JSON or BSON objects.

Which is more flexible - SQL or MongoDB? and why.
This is an easy one, and a hands down win for MongoDB. The schemaless design of MongoDB documents makes it extremely easy to build and enhance applications over time, without needing to run complex and expensive schema migration processes as you would with a relational database.

With MongoDB, there are more dynamic options for updating the schema of a collection, such as creating new fields based on an aggregation pipeline or updating nested array fields. This benefit is particularly important as databases grow in size. In contrast, larger MySQL databases are slower to migrate schemas and stored procedures that can be dependent on the updated schemas. MongoDB’s flexible design makes this much less of a concern.

What is the disadvantage of a NoSQL database?
1-don’t have the reliability functions which Relational Databases have (basically don’t support ACID(Atomicity, Consistency, Isolation, and Durability).

2-In order to support ACID developers will have to implement their own code, making their systems more complex.

3-This may reduce the number of safe applications that commit transactions, for example bank systems.

4-are very new compared to Relational Databases, which means that are far less stable and may have a lot less functionalities.

 NOSQL .