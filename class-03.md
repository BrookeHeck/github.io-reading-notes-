# HTML Lists, Control Flow with JS, and the CSS Box Model

## Summary
The first reading section highlights lists in HTML. To correctly format a list in HTML, you actually need to use to html tags, the ul or ol tags to identify the content as a list, and then the li tag for each list item. Lists have attributes that allow you to change the styling through css. Lists are important because they is one more important tool that helps a developer structure a website so that it makes sense to a user.
\
Understanding the CSS box model is important for being able to style an element to exactly how we want it to look. The box model includes margin, border, padding, and content. In order to correctly space or style an element, you need to know which part of the element you are trying style so that the right selector is used.
\
Arrays, expressions, operators, and conditionals all continue to add functionality to our code. Arrays are super helpful for storing or grouping data in our JS and allow for easy access with an index when we want to use that data. We can take that data and use it in our expressions, add operators to solve problems, and use conditionals to execute different blocks of code. Learnig about all these are important for writing code that accomplishes something.

## Learn HTML
1. When should you use an unordered list in your HTML document?
- An unordered list is helpful when you are trying to group some content that is makes sense to go together, but doesn't need to be in a numbered order.
2. How do you change the bullet style of unordered list items?
- The attribute type can change the type of bullet to circle, disc, or square. A fourth bullet type, triangle, is not compatible with all browsers.
3. When should you use an ordered list vs an unorder list in your HTML document?
- Ordered lists are similar to unordered list in that way that you want to group content that goes together, but use an ordered list when it the list makes sense in numerical order.
4. Describe two ways you can change the numbers on list items provided by an ordered list?
- UL numbers can be changed in a style sheet using list-style-type property.
- UL numbers can be changed with the attribute type and setting it to a for letters, A for uppercase letters, i for Roman numerals, I for uppercase Roman numerals, and 1 for default.

## Learn CSS
1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
- Margin is the outermost part of the box model and is the spacing between that element and other elements around it.
- Padding is not the space around the element, but instead the space around the content. Adding a border to an element and increasing the padding is an easy visual representation of padding. As the padding increases, the spacing between the content and the border will increase.

2. List and describe the four parts of an HTML elements box as referred to by the box model.
- Content: this is what is inside HTML tags and actually displays on a webpage
- Padding: The space around the content
- Border: wraps the content along with any padding
- Margin: outermost part and is the space around the entire element

## Learn JS
1. What data types can you store inside of an Array?

2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
``` 
const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
```
- Yes this is a two dimensional array and is valid in JS. You would access values in this array by using two indices. For example, the following code would give you the value 'accountant'.
``` let job = people[1][2]; ```

1. List five shorthand operators for assignment in javascript and describe what they do.
- += will take the left operand and add the right operand to it
- -= will take the the left operand and subtract the right operand from it.
- **= is the exponentation assignment. It will raise the value of the left operand to the value of the right operand
- ||= is the OR shorthand and works by only evaluating the right operand if the first operand is false. This makes sense because if the first expression is true, then the entire statement is true no matter what the second one is and there is no need to evaluate it.

2. Read the code below and evaluate the last expression and explain what the result would be and why.
```
 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;
 ```
 - The plus sign will be used to concact the the variables into a string. Although 10 is a number, it cannot be added to a string or boolean, so the code will use them all as strings. The expression will evaluate 10dogfalse.

1. Describe a real world example of when a conditional statement should be used in a JavaScript program.
- An example of a time to use a conditional is when changing the balance of a bank account. If somone makes a withdrawal, then you would subtract that money from the account. If they make a deposit, then the money should be added to the account.

2. Give an example of when a Loop is useful in JavaScript.
- A loop is useful anytime that you need to iterate through data, but for a specific example, an array would help display a gallery of photos. If there were 100 photos to display, you wouldn't need to write out an img element and a src attribute for each one. Instead you could use JS to make a function that accepts all the img sources in an array. The function could loop through the array and create an image element, assign the array value as the src attribute, and append it to the HTML section. This function would only be a few line of codes instead of the hundreds to create each html element separatley.

## Things I want to know more about

### Links
[Ordered lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
\
[Unordered lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)
\
[The box model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)
\
[Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)
\
[Expressions and Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
\
[Making decisions in your code — conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)



