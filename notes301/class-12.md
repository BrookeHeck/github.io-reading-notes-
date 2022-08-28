# CRUD

## Summary
The first article went over the different HTTP status codes in depth. This was good to know because although a lot of servers will default to 500 or 404 error responses, this isn't always correct. Responding with correct status code can help the client figure out if their request was valid and handled correctly, or if the request was not valid and why it was not successful.

The video was a quick walk through for setting up a MongoDB using Express and Mongoose.

## Status Codes Based On REST Methods
1. In your own words, describe what each group of status code represents:
    - 100’s = Information status codes
    - 200’s = Success codes
    - 300’s = Redirection codes
    - 400’s = Client error codes
    - 500’s = Server error codes

2. What is a status code 202?

    This code means accepted. A 202 often means that the request was valid, but it is still processing and will finish in the future.

3. What is a status code 308?

    A 308 status code tells the user that they nee to use another url to access this resource.

4. What code would you use if an update didn’t return data to a client?

    204 No Content

5. What code would you use if a resource used to exist but no longer does?

    410 Gone

6. What is the ‘Forbidden’ status code?

    This is when a user doesn't have permission to access a resource.

## Build a REST API With Node.js, Express, & MongoDB
1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?

    When we deploy the database, we don't want to use localhost to handle the server requests. We can fix this by pulling the database string out of the server and adding it the environment variables file.

2. What is middleware?

    Middleware is code that runs between the user getting a request and that request being passed to the route.

3. What does app.use(express.json()) do?

    This is middleware that will allow our server routes to accept json.

4. What does the /:id mean in a route?

    The id is a parameter that will be passed to the route in the get request. We can access the parameter by using the request object and getting the params value.

    ``` let userID = request.params.id ```

5. What is the difference between PUT and PATCH?

    PUT is used to create a new user in the database while PATCH is used to update an existing user.

6. How do you make a default value in a schema?

    When you are creating an object to pass to the new Schema object, use the key default and give it whatever value you want the default to be.

7. What does a 500 error status code mean?

    A 500 status code means that the server had an error that cause the request to fail.

8. What is the difference between a status 200 and a status 201?

    A 200 means the request was successful, but a 201 is a more specific status that lets the user know that the data was successfully created and added to the database.

## Things I want to learn more about

### Links
[Which HTTP Status Code to Use for Every CRUD App](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

[Build a REST API With NOde.js, Express, & MongoDB](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)
