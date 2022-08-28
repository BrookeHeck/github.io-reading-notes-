# More CRUD

## Summary
These articles built more off of yesterdays readings. The first article is relating the HTTP methods to CRUD. For example, to read something from a web API we would probably use the HTTP method get. To create something, we would use POST.

The video was another code walk through for setting up the bare bones of a MongoDB using Node.js and Express.

## CRUD Basics
1. Which HTTP method would you use to update a record through an API?

    PUT

2. Which REST methods require an ID parameter?

    PUT and DELETE

## Speed Coding: Building a CRUD API
1. What’s the relationship between REST and CRUD?

    REST is an architecture for building APIs, and CRUD are four functions that are often used in web APIs. They are related because when you make a REST API, you are probably using CRUD or something like that. Also, a lot of web APIs communicate using HTTP, which the HTTP functions are very similar to the CRUD functions.

2. If you had to describe the process of creating a RESTful API in 5 steps, what would they be?

  - Bring in express and router, export the router
  - Use router to make routes for create, read, update, delete
  - mount the router by using the routing in the server.js file
  - set a port and Mongo URI in the .env file
  - use the database by passing in the Mongo URI string

## Things I want to learn more about

### Links
[CRUD Operations Explained](https://medium.com/geekculture/crud-operations-explained-2a44096e9c88)

[Build a CRUD API with Node.js, Express, MongoDB](https://www.youtube.com/watch?v=EzNcBhSv1Wo)