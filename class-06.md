# Problem Domain, Objects, and the DOM

## Summary
The first article describes how to create objects in JavaScript. Objects are usefule for grouping data that goes together and provides more meaningful structure than an array. You can access the properties of an object by calling on that object and then using dot or bracket notation to call the property. Objects are also used so you don't have to keep repeating code. Instead, you can create a constructor that creates a template of an object. Parameters are passed into constructors so that each object created has properties that are specific to that object.
\
\


## JavaScript Object Basics

1. How would you describe an object to a non-technical friend you grew up with?
- Sorry for being unoriginal because this is a common analogy, but an object is like a blueprint to a house. The blueprints can contain many aspects like the square footage, number of rooms, type of materials used, or the color of the house. These would be like the variables in an object. If the blueprings included heating, electric, or plumbing these could be thought of as functions within that object.

2. What are some advantages to creating object literals?
- Objects provide a structure that allow you to group related data. This is helpful because you don't have to declare a bunch of variables and try and remember what data goes with what. Instead you can create an object and access that specific data by calling on the object.
- To go with my previous analogy, if you had a bunch of houses and were trying to figure out what the color of a specific house is, you can call on that specific house object and get the color of that particular house.

3. How do objects differ from arrays?
- You could put all your data into an array, but an object provides more structure and easier access than using an index. If you were trying to access data from an array, you would need to remember or find the index, but for an object you can just call the variable or function name. Getting the right data could become even more confusing when using multi-dimensional arrays.

4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
- Dot notation is more common when accessing an object property, but brackets would be required if an object property name is defined at runtime instead of defined inside the object.

5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?
- The keyword this is used when referring to the current object when writing code within that object. So in this example, this.name is referring to the object dog's name and that same object's age. So this.name is 'Spot' and this.age is 2.

## Introduction to the DOM
1. What is the DOM?
2. Briefly describe the relationship between the DOM and JavaScript.

### Links
[JavaScript object basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)
[Introduction to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
