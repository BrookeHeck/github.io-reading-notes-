# Problem Domain, Objects, and the DOM

## Summary
The first article describes how to create objects in JavaScript. Objects are useful for grouping data that goes together and provides more meaningful structure than an array. You can access the properties of an object by calling on that object and then using dot or bracket notation to call the property. Objects are also used so you don't have to keep repeating code. Instead, you can create a constructor that creates a template of an object. Parameters are passed into constructors so that each object created has properties that are specific to that object.
\
The second article explains how HTML elements are used as objects by JavaScript to manipulate the webpage. By using the elements as objects, you can make a webpage much more interactive and even change how elements look or create and delete elements based on what the user is doing.
\This is important to what we are learning becuase the websites we create would be pretty boring without it. We could provide content in a structured and meaningful way, but using JavaScript and the DOM allows us to create really cool websites that have function and interactivity.



## JavaScript Object Basics

1. How would you describe an object to a non-technical friend you grew up with?
- Sorry for being unoriginal because this is a common analogy, but an object is like a blueprint to a house. The blueprints can contain many aspects like the square footage, number of rooms, type of materials used, or the color of the house. These would be like the variables in an object. If the blueprints included heating, electric, or plumbing these could be thought of as functions within that object.

2. What are some advantages to creating object literals?
- Objects provide a structure that allow you to group related data. This is helpful because you don't have to declare a bunch of variables and try and remember what data goes with what. Instead, you can create an object and access the data that goes with that specific object.
- To go with my previous analogy, if you had a bunch of houses and were trying to figure out what the color of a specific house is, you can call on that specific house object and get the color of that particular house.

3. How do objects differ from arrays?
- You could put all your data into an array, but an object provides more structure and easier access than using an index. If you were trying to access data from an array, you would need to remember or find the index, but for an object you can just call the object and property name.

4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
- Dot notation is more common when accessing an object property, but brackets would be required if an object property name is defined at runtime instead of defined inside the object.

5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?
- The keyword this is used when referring to the current object when writing code within that object. So in this example, this.name is referring to the object dog's name and this.age to that same object's age. So this.name is 'Spot' and this.age is 2.

## Introduction to the DOM
1. What is the DOM?
- DOM represents an HTML page and it's elements as nodes and objects that can be used with JavaScript.
2. Briefly describe the relationship between the DOM and JavaScript.
- The DOM is essential for being able to create, update, change, and access different HTML elements on a webpage. When you think of a HTML element as just markup on a webpage it only provides the user with structure, but when you think of a HTML element as a JavaScript object, there is way more you can do with an element. The element can now have different properties and functions, and JavaScript can be used to change those properties based on how a user interacts with it. The DOM is key to making dynamic webpages.

## Things I want to know more about
- I didn't know the DOM was part of a web API, but it makes sense that it is independent from JavaScript so that other programming languages can use it. I would like to know more about how JavaScript interacts with this API.

### Links
[JavaScript object basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)
\
[Introduction to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
