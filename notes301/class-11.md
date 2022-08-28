# SQL vs NoSQL

## Summary
Today's reading focused on the differences of SQL and NoSQL. SQL is a relational database that uses strict schemas to store data. This can be an advantage because it provides predictability and updating data can be easier because it uses relations, but this means the database scales vertically and this is not always great for large amounts of database.

NoSQL is a distributed database that is document based. There is a lot more flexibility with what can be stored in the documents. It doesn't provide the same predictability and relations that SQL does, but this type of database scales horizontally which means it can be scaled easily by adding more servers and queries are usually quicker.

## NoSQL vs SQL
Differences Table
<table>
  <tr>
    <td>SQL<td>
    <td>NoSQL<td>
  <tr>
  <tr>
    <td>relational<td>
    <td>non-relational or distributed<td>
  <tr>
  <tr>
    <td>table-based<td>
    <td>document-based<td>
  <tr>
  <tr>
    <td>pre-defined schema<td>
    <td>dynamic schema<td>
  <tr>
  <tr>
    <td>vertically scalable<td>
    <td>horizontally scalable<td>
  <tr>
  <tr>
    <td>structured query language<td>
    <td>unstructured query language<td>
  <tr>
<table>
<br/>

1. What kind of data is a good fit for an SQL database?

    SQL databases are best for complex queries

2. Give a real world example.

    SQL is very defined and reliable so using SQL databases is a common choice for banking and financial institutions.

3. What kind of data is a good fit a NoSQL database?

    SQL is not a good fit for hierarchial data storage

4. Give a real world example.

    NoSQL is good for handling large sets of data that is less structured. Social networks often ue NoSQL databases.

5. Which type of database is best for hierarchical data storage?

    NoSQL databases are best for hierarchical data storage

6. Which type of database is best for scalability?

    Both types are scalable, but sql manages increasing load with more CPU, RAM, or SSD. NoSQL is easily scalable by just adding more servers in the infrastructure to handle more traffic.

## sql vs nosql (video)
1. What does SQL stand for?

    Structured Query Language

2. What is a relational database?

    A relational database uses tables that works as a data bin. The table has specific fields and every new entry has values for these fields.

3. What type of structure does a relational database work with?

    Relational databases use tables

4. What is a ‘schema’?

    A schema is a collection of database objects.

5. What is a NoSQL database?

    A no NoSQL database is used to store large amounts of data. It is a distributed database that uses collections instead of strict schema.

6. How does it work?

    The NoSQL database works by having collections and then within those collections, documents. The documents can be similar to a schema, but not every object in that document needs to hold the same data. 

7. What is inside of a Mongo database?

    Collections and documents

8. Which is more flexible - SQL or MongoDB? and why.

    MongoDB is more flexible because you don't have to adhere to a strict schema. The data doesn't have to be uniform and you can format it how you like.

9. What is the disadvantage of a NoSQL database?

    There is less relationships in NoSQL, so although you can make faster queries, the disadvantage is that there is sometimes duplicate data, and if something changes you may have to update that data in multiple places.

## Things I want to learn more about

## Links
[SQL vs NoSQL Database Differences Explained](https://www.thegeekstuff.com/2014/01/sql-vs-nosql-db/?utm_source=tuicool)

[SQL vs NoSQL or MySQL vs MongoDB](https://www.youtube.com/watch?v=ZS_kXvOeQ5Y)

[Model](https://mongoosejs.com/docs/api.html#Model)

[React Router](https://v5.reactrouter.com/web/api/BrowserRouter)
