# Functional Programming

## Summary
The first article talked about good practices for creating functions that are stable so that they are less likely to cause errors in other places of an application. Using pure functions and immutable data gives codes this stability. What this means is that the function relies on the parameters that are passed into it in order to return a result. This means the same result will always be returned for the same input.

The video introduced node modules. This is just a way of creating js files that have only one purpose. When we want to use that module in our app, we must export the function or data that we want from that module and then require it in the app.js file in order to use there.

## Functional Programming Concepts
1. What is functional programming?

    Functional programming is a way of structuring code that keeps it simple by having functions that do single operations and are immutable.

2. What is a pure function and how do we know if something is a pure function?

    A pure function is one that will always return the same result if it is given the same arguments.

3. What are the benefits of a pure function?

    Pure functions don't impact other parts of our code. If we use them to update a global variable, then these functions could cause errors if that same global variable is used somewhere else. Pure functions are stable and predictable. Pure functions are also easier to test.

4. What is immutability?

    Immutability means that it does not change.

5. What is Referential transparency?

    A function that consistently gives the same result for the same input is referentially transparent. Pure functions and immutable data give us referential transparency.

## Node JS Modules and require()
1. What is a module?

    A module is a file in our application that serves a specific purpose and only does one thing in the application. We only call the module when we need it.

2. What does the word ‘require’ do?

    Require is a global method in js that takes in a path as a parameter and will return anything that is exported in that path.

3. How do we bring another module into the file the we are working in?

    We must declare a variable and use the require method in order to get the exports from that file.

    ``` const counter = require('./counter.js'); ```

4. What do we have to do to make a module available?

    We use the exports function.

## Things I want to learn more about

### Links
[Concepts of Functional Programming in Javascript](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

[Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k)