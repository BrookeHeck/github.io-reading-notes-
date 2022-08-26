# APIs

## Summary
This article talked about best practices for designing web APIs. This includes how to make good URIs and also creating REST APIs so that requests can be made to those URIs. It also touched briefly on some formats that data can be stored and delivered when requests are made to that endpoint. Finally, the article went over some of the common verbs used for making requests and what type of status codes should be used for responding with success or failure to a request.

## API Design Best Practices
1. What does REST stand for?

    Representation State Transfer, it is an architecture design for handling web services. The most common REST API uses HTTP.

2. REST APIs are designed around a ____.

    resources, any kind of object, data, or service that a client can access

3. What is an identifier of a resource? Give an example.

    A URI, which a unique identifier to a resource.
    - https://adventure-works.com/orders/1

4. What are the most common HTTP verbs?

    GET, POST, PUT, PATCH, and DELETE

5. What should the URIs be based on?

    Good URIs should be based on the noun and not the verb

6. Give an example of a good URI.
    ```
    https://adventure-works.com/orders // Good

    https://adventure-works.com/create-order // Avoid
    ```

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

    Chatty web APIs expose a large number of small resources. This is generally a bad thing because there are lot more requests being made to the API and this is a heavier load on the web server.

8. What status code does a successful GET request return?

    200 (OK)

9. What status code does an unsuccessful GET request return?

    400 (Not Found)

10. What status code does a successful POST request return?

    201 (Created)

11. What status code does a successful DELETE request return?

    204 (No Content)

## Things I want to learn more about

### Links
[RESTful web API design](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

[RegExr](https://regexr.com/)

[Regex tutorial — A quick cheatsheet by examples](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)

[Regular expressions 101](https://regex101.com/)
