# Introductory HTML and JavaScript

## Summary
The getting started portion of the reading started with the basics of how web pages are retrieved from servers where the source code resides and is eventually displayed for the client. The browser acts as the go between for the server and client by making requests, parsing code returned by the server, and displaying that code to the client. Other readings in the section included the basics of HTML and JS. HTML, JS, and CSS work together to create webpages when parsed and rendered by a browser. HTML and CSS are markup languages that give structure and style to a webpage while JS gives a webpage interactivity.
\
Introduction to HTML was the next reading section, and was a deeper dive into how HTML provides the structure of a webpage. Elements within the body of an HTML file put content in ordered way that the browser understands and can parse. The header is another important aspect of HTML because it provides the metadata, which is data about the HTML. This is used by the browser to correctly render the page.
\
The last section of reading provides a few different, but helpful readings. The first article describes how having purpose and vision is the most important part of web design. This is so the website has meaning by accomplishing a specific goal. The next article went over the importance of semantics in HTML. Following customs helps developers, browsers, search engines, and screen readers. The last reading went over JavaScript and it's crucial role in developing dynamic websites.

## Getting Started
1. Compose a short poem describing how HTTP sends data between computers.
Make a request to the DNS
\
Receive the IP address
\
Send the server an HTTP request
\
A 200 OK means you can access
\
The server sends files to process
\
The browser assembles to visually express

2. Describe how HTML, CSS, and JS files are “parsed” in the browser.
- The browser begins with parsing the HTML code sent returned by an external server and uses this to recognize CSS and scripts that are needed to render the webpage. The browser continues to parse the HTML code, but also sends requests to the server for the CSS and js files. Next, the browser parses the CSS and js files. With the parsed code, a DOM tree is made with the HTML, a CSSOM tree is made with the CSS, and JavaScript code is compiled and executed. The browser applies the styles from the CSSOM to the DOM and executes JavaScript to show a visual representation of the code to a user.

3. How can you find images to add to a Website?
- Images can be added by searching Google Images and either saving the image to somewhere in your local directory or by copying the web address. Google has a license filter to use so that copyright laws are not broken.
- [Unsplash](https://unsplash.com/) is a really cool website that has thousands of free images that can be used.

4. How do you create a String vs a Number in JavaScript?
- A string should have quotes (single and double both work in javascript)
\
``` let str = 'This is how to make a string'; ```
- Numbers don't have quotes
\
``` let num = 19; ```

5. What is a Variable and why are they important in JavaScript?
- Variables are used to store values in JavaScript. Variables allow us to write dynamic code that changes variables. This makes programs interactive or personalized.

## Introduction to HTML
1. What is an HTML attribute?
- Attributes part of an element, but provide information about the element instead of being displayed on the screen. For example, an element could be given an id attribute which is used in the CSS to select that element and style it.
\
``` <section id="intro">Here is an introduction section</section> ```
- There are many more attributes that help change the styling of the element or how the user interacts with the element.

2. Describe the Anatomy of an HTMl element.
  1. opening tag: name of element wrapped in brackets, marks beginning of element, attributes can be added inside the opening tag
  2. content: what ever data you want inside the element
  3. closing tag: sam as opening tag but marks the end of an element

3. What is the Difference between <article> and <section> element tags?
- An article has content that would make sense on it's own even if it didn't have the rest of the website content
- A section is a smaller grouping that wouldn't make sense by itself but has a similar theme. Multiple sections might make up an article.

4. What Elements does a “typical” website include?
  1. ``` <DOCTYPE htmL> ```
  2. ``` <htmL></html> ``` wraps all the content on the page, root element
  3. ``` <head></head> ``` container for things that aren't content; keywords, CSS style content, character set declarations
  4. ``` <meta charset="utf-8"> ```
  5. ``` <title></title> ``` sets the title of the page that appears on the browser tab
  6. ``` <body></body> ``` displays all content on the page; tet, images, videos, games, audio and anything else</br>
  - the body often contains header, nav, main, and footer elements

5. How does metadata influence Search Engine Optimization?
- Descriptions about the content of the site within the metatag can serve as keywords in search engines. This can help the site appear higher among the relevant search results.

6. How is the <meta> HTML tag used when specifying metadata?
- The meta element is the official way of adding metadata to an HTML file. There is multiple tags in the header that can be used to specify metadata, but the meta tag is one of them. In this tag you can find attributes such as the character set, name, or content.

## Miscellaneous
1. What is the first step to designing a Website?
- The first step in designing a website is to know the purpose, or in other words, what are you trying to accomplish by creating this website? Even with good technical skills, a website could still be lacking or confusing without any planning or vision. This is call project ideation.

2. What is the most important question to answer when designing a Website?
- The most important question is, what do I want to accomplish?

3. Why should you use an <h1> element over a <span> element to display a top level heading?
- There are many reasons to use correct semantic markup. One of them is that browsers will automatically render them to look like important headings. The browser will not automatically give helpful styling to a span or any tag that is not meant to be a heading.
4. What are the benefits of using semantic tags in our HTML?
- The MDN page, [Semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics) provides a good list of reasons.
  - Important keywords will influence the search engine ranking
  - Screen readers use html elements as guides to help people who are visually impaired
  - Finding blocks of meaningful code is easier
  - Suggests to the developer what data they will see here
  - Semantic naming mirrors proper custom naming

5. Describe 2 things that require JavaScript in the Browser?
- JavaScript is required to store variables and respond to clicks by using event listeners. There are many other things that JavaScript can do within a browser, but these are two basic examples.

6. How can you add JavaScript to an HTML document?
- JavaScript can be added to HTML using the script tag. JavaScript can be written directly into this tag, or you can use the attribute src to link and external js file.

## Things I want to know more about
- I have much more of a coding background than a networking background. I do know that sending data back and forth is important part of being able to provide the source code and data to the user. I would like to know more about internet protocols and how requests are made and fulfilled.
- Working with API's is such an important part of web development. I would like to know about the ins and outs of how APIs work and how to use them.
- SEO is a hot topic right now, with many businesses trying to be as high as possible in order of search engine results. Other than adding content keywords to the metatag, are there more ways to improve SEO?
