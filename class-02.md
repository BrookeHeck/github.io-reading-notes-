# Basics of HTML, CSS & JS

## Summary
The first section continued with more HTML. There weren't really any new concepts here, but many more elements were introduced. It is important to use these tags so that users, developers, search engines, and screen readers have a better understanding of the content on the page. This reading section also introduced how to incorporate CSS to style a HTML page. CSS is important for styling a webpage, which can also help with a more structured, organized webpage and also just a more visually appealing site.
\
The second section of reading went deeper into JS. We already learned about data types, but variables, operators, and conditionals allow us to use data in a meaningul. Being able to manipulate data allows us to solve real world problems through coding. Knowing how all three of these work together is very important because they are what a browser uses to render a webpage.


## Introduction to HTML
1. Why is it important to use semantic elements in our HTML?
- The MDN page, [Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics) provides a good list of reasons.
  - Important keywords will influence the search engine ranking
  - Screen readers use html elements as guides to help people who are visually impaired
  - Finding blocks of meaningful code is easier
  - Suggests to the developer what data they will see here
  - Semantic naming mirrors proper custom naming

2. How many levels of headings are there in HTML?
- There are six levels of headings in the HTML structure. Usually there is one h1 for the title of the page and then within the page are the higher number headings for sections and sub-sections.

3. What are some uses for the sup and sub elements?
- Both superscripts and subscripts are used in math. So formulas or equations could require the use of sup and sub tags.

4. When using the abbr element, what attribute must be added to provide the full expansion of the term?
- The attribute title inside an abbr tag will provide the full expansion of the abbreviated term.

## Learn CSS
1. What are ways we can apply CSS to our HTML?
- CSS can be applied either internally or externally. Internal CSS styles can be found as attributes inside the opening tag of an element. External sheets are linked to the HTML page in the header.

2. Why should we avoid using inline styles?
- For sites with lots of HTML elements, this becomes a very inefficient way of applying CSS because it must be applied to every element. When you use an external CSS sheet, you can use a CSS selector to style multiple HTML elements with one block of code. 


3. Review the block of code below and answer the following questions:
```   
  h2 {
     color: black;
     padding: 5px;
   } 
```
- What is representing the selector? The h2 is the selector
- Which components are the CSS declarations? A declaration is a property paired with its value
- Which components are considered properties? The properties are color and padding

## Learn JS
1. What data type is a sequence of text enclosed in single quote marks?
- The string datatype is enclosed in single quotes.
``` let str = 'MyString:)' ```

2. List 4 types of JavaScript operators.
- Four JS operators are assignment, strict equality, additon, and does not equal.

3. Describe a real world Problem you could solve with a Function.
- For my last job we would need to get the weight of a pallet before we could load it onto an aircraft. But we would need to find two different weights, the gross weight and the net weight. The net weight is just the weight of the cargo, so we would have to add up the weight of the pallet, nets, and straps to subtract from the gross weight. It would be nice to have a function that figures out the tare weight by taking the number of restraints used and returning the net weight by subtracting tare weight from the gross weight.

4. An if statement checks a __ and if it evaluates to ___, then the code block will execute.
- expression
- true

5. What is the use of an else if?
- An if else statement only has one expression and two blocks of code that can possibly run. If we put and else if into the mix, then we can evaluate multiple expressions and have different blocks of code run based on what we want the program to do.

6. List 3 different types of comparison operators.
- AND &&
- OR ||
- GREATER THAN >
- NOT EQUALs !==

7. What is the difference between the logical operator && and ||?
- For the && operator to evaluate to true, both expressions must be evaluate to true. If either one of them is false, the entire statement is false.
- For the || operator to evalutate to true, only one expression needs to be true. The only way it will evaluate to false is if both expressions are false.

## Things I Want to Learn More About
- I learned a ton of new HTML elements. I've always used super basic ones, and fallen into the bad habit of using a bunch of divs and putting content in there without any html tags. It's not really something I want to know more about, but something I would like to get more practice with.
- Same or CSS selectors. There are a lot that I've never used and could use more practice with.

### Links
[HTML text fundamentals](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals)
\
[Advanced text formatting](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Advanced_text_formatting)
\
[How CSS is structured](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)
\
[JavaScript basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
\
[Making decisions in your code - conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)