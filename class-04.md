# HTML Links, JS Functions, and Intro to CSS Layout

## Summary
Anchor elements are very common and incredibly useful HTML elements. They link the web to other parts of the web and makes moving between sites and finding helpful information super easy. Learning to create working anchor elements is important becasue it is a common function of many websites that users will find helpful.
\
In previous readings, I learned how to style specific HTML elements, but this reading taught about how to position them as well. There is the default positioning, but based on the content it might make more sense or look better to position elements next to one another, wrapped within one another, or overlapped. Changing the flow and positioning of the document can do all these things.
\
JS functions are very helpful when it comes to the DRY (Don't Repeat Yourself) principle. Functions create reusable blocks of code. I can define a function and what I want it to do, and then invoke it over and over again within my code so that I don't have to rewrite the code within the function. Parameters are an important part of this because parameters allow me to execute the same function on multiple different variables.

## HTML, Creating Hyperlinks
1. To create a basic link, we wrap text or other content inside what element?
- Links are wrapped inside an anchor element. Here is an example.
\
``` <a href="example.com>This is an anchor element</a> ```

2. The href attribute contains what information?
- The href attribute contains the target of the link. In other words, when you click the anchor html element, this is the URL the user will be taken to.

3. What are some ways we can ensure links on our pages are accessible to all readers?
- use clear wording
- make it clear when a link directs a user to something other than another html page
- use the download attribute for linking to downloads

## CSS Layout
1. What is meant by “normal flow”?
- Normal flow is the default way a browser will layout HTML elements if no specific positioning is given for the elements.

2. What are a few differences between block-level and inline elements?
- Block elements take up the entire width of the page. This means each block element will appear on it's own horizontal line unless changed with CSS.
- Inline elements only take up the width determined by the content within that element. These elements can be wrapped inside of other content and can sit on the same line as other elements.

3. ___ positioning is the default for every html element.
- Static

4. Name a few advantages to using absolute positioning on an element.
- Absolute positioned elements don't exist in the normal document flow. This means we can overlap them with other elements and create pop-up boxes or GUIs over other content on the screen.

5. What is a key difference between fixed positioning and absolute positioning?
- Absolute positioning places an element in rleation to its nearest ancestor.
- Fix positioning fixes the element in relation to the visible viewport. This would help make some items 'stick' to one spot on the screen, which may be helpful for a nav bar or a pop-up.

## Learn JS
1. Describe the difference between a function declaration and a function invocation.
- A function declaration defines the name of the function, parameters that will be passed to it, and the block of code that will execute when it is called.
```
 function sayHello(username) {
  alert(`Hi ${username}`);
 }
```
- Function invokation is actually using a function after it has been declared.
```
 sayHello('Tom');
```

2. What is the difference between a parameter and an argument?
- Parameters are specified in the parentheses and is a variable that the function requires to execute.
- An argument is when an actual value is passed into the function to be used by that function.

## Miscellaneous
1. Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.
- Learning from fellow students is definitely a benefit from pair programming. Everybody has different levels of experience with coding and just previous life experience in general. There is always something to learn from somebody else's code, or I could learn from having a partner incorporate their knowledge into my own code.
- Greater efficiency is another benefit of pair programming. A second set of eyes could catch a bug that wasn't previously noticed, or see a more eficcient way of coding something.

## Things I want to learn more about
- Flexbox is a cool way of positioning elements without having to do any math. I have heard of flexbox, but never actually used it, so I would like to learn more about it.
### Links
[Creating hyperlinks](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)
\
[CSS layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout)
\
[Normal flow](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow)
\
[Positioning](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning)
\
[Functions](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions)