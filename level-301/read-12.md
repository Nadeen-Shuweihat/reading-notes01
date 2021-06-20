# Mongo and Mongoose

Fill in the chart below with five differences between SQL and NoSQL databases:

       SQLNoSQLSQL databases are primarily called as Relational Databases (RDBMS)database are primarily called as non-relational or distributed database.SQL databases are table based databasesdatabases are document based, key-value pairs, graph databases or wide-column stores.databases have predefined schema whereasdatabases have dynamic schema for unstructured data.databases are vertically scalable whereasdatabases are horizontally scalable.databases uses SQL ( structured query language ) for defining and manipulating the data, which is very powerfuldatabase, queries are focused on collection of documents.

- What kind of data is a good fit for an SQL database?
 
    > If the data is numeric, favor SMALLINT, INTEGER, BIGINT, DECIMAL, character, or data types. 

- Give a real world example.

     > MySQL database is very popular open-source database. It is generally been stacked with apache and PHP, although it can be also stacked with nginx and server side javascripting using Node js.
     
- What kind of data is a good fit a NoSQL database?

    > highly preferred for large data set (i.e for big data). Hbase is an example for this purpose.

- Give a real world example.

      > Mongodb is one of the most popular document based NoSQL database as it stores data in JSON like documents. 

- Which type of database is best for hierarchical data storage?

     > NoSQL database. 

- Which type of database is best for scalability?

    > Structured Query Language. 

- What does SQL stand for?

    > Structured Query Language. 

- What is a realational database?

   > is a type of database that stores and provides access to data points that are related to one another.

- What type of structure does a relational database work with?
  
  > B-TREE ,collection of tables, each having a unique name. A row in a table represents a relationship among a set of values. Thus a table represents a collection of relationships. There is a direct correspondence between the concept of a table and the mathematical concept of a relation. 

- What is a ‘schema’?
     
    > Is a cognitive framework or concept that helps organize and interpret information, represents the logical configuration of all or part of a relational database.

- What is a NoSQL database?
      
      > which stands for “not only SQL,” is an approach to database design that provides flexible schemas for the storage and retrieval of data beyond the traditional table structures found in relational database. 

- What is inside of a Mongo database?

     > MongoDB stores data records as documents which are gathered together in collections. A database stores one or more collections of documents. 

- Which is more flexible - SQL or MongoDB? and why.

       > MongoDB, some research has shown that the speed of MongoDB could be 100x faster than a relational database, and it has easy setup. 

- What is the disadvantage of a NoSQL database?

      > don’t have the reliability functions which Relational Databases have (basically don’t support ACID). 