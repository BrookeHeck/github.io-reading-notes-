# Object-Oriented Programming, HTML Tables

## Summary

## Domain Modeling
1. Explain why we need domain modeling.
- Domain modeling is critical for being able to create many objects with the same properties. This is helpful for writing dynamic code that can create objects based on user input. It also means we have to write way less code. For example, a website could create a user profile constructor, and use that same constructor to create thousands of profiles.

## HTML Table Basics
1. Why should tables not be used for page layouts?
- tables are difficult for visually impaired users that are on the website with a screen reader
- using a table to layout a website involves more complex markup structures
- tables aren't responsive, meaning they can be diffiuclt to read if the table wasn't created for that size screen

2. List and describe 3 different semantic HTML elements used in an HTML table.
- table is used as a tag to wrap all the contents of the table
- td tags for table data are the indiviual cells of the table
- tr tags for rows wrap the td tags to create the table rows

## Introducing Constructors
1. What is a constructor and what are some advantages to using it?
- A constructor is a function that creates an object with specific properties. The values to these properties can be passed into the function to create multiple objects with the same properties but different values. This is super helpful because you don't have to write out an object with all those properties over and over again to create objects with different properties. Functions can also be added within the constructor. This is helpful for the same reason because you don't have to write functions specific to each object, but that function will work on all objects of the same type.

2. How does the term this differ when used in an object literal versus when used in a constructor?
- When this is used inside of a constructor, it is referring to that property within the constructor. It is often used to initialize properties with values.
- When this is used with an object literal, it is referring to the value of that property for that specific object.

## Object Prototypes Using a Constructor
1. Explain prototypes and inheritance via an analogy from your previous work experience.
- An analogy for prototypes and inheritance from my last job would be thinking of a generic cargo jet as the prototype. The properties inherited by all cargo aircrafs could be name, number of pallets positions, maximum number of passenger seats, max cargo weight capacity. All cargo aircrafts would have these properties, but they wouldn't be the same for each specific aircraft.

## Things I would like to know more about

### Links
[Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)
\
[HTML table basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)
\
[JavaScript object basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)
\
[A Beginner's Guid to JavaScript's Prototype](https://ui.dev/beginners-guide-to-javascript-prototype)
\
[HTML table advanced features and accessibility](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)