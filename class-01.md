# Introductory HTML and JavaScript

## Getting Started

### Getting started with the web
- install basic software</br>
  editors, browsers, graphics editors, FTP, version control system
- website design
   1. planning - what information will be on your website
   2. sketch a design - what will yor website design be
   3. choose assets - put together content that will be on your website
- dealing with files</br>
  html, css, js, and image files should be structured in a way that makes sense and in a way that allows each file to be called upone easily </br>
  don't use spaces, browsers, web servers, and programming languages don't handle spaces the same way
- HTML basics</br>
  HTML structures the content on your webpage</br>
  headers, paragraphs, lists, and many other HTML elements help put the information in a way that makes sense to the user
- CSS basics</br>
  While HTML provides structure, CSS helps give the website a design</br>
  color, spacing, fonts, alignment, and more
- JS basics</br>
  makes the website interactive with the user
  event listeners, animation, styling effects, and more

### How the web works
- Clients </br>
 users's interent devices and web-acessing software, they make requests to a server
- Servers</br>
 computers that store webpages, sites, or apps</br>
 servers respond to requests from clients with information, it could be an endpoint that   returns data or could return html/css/js files for the browser to render as webpages

- Other pieces of the puzzle</br>
  1. your internet connection
  2. TCP/IP - internet protocols that help define how data travels across networks
  3. DNS - > Domain Name System is like an address book for websites. When you type a web address in your browser, the browser looks at the DNS to find the website's IP address before it can retrieve the website
  4. HTTP - protocol for how clients and servers communicate
  5. Component files - code files and assets

- What happens exactly?
  1. browser uses DNS to find IP address of server the website is hosted
  2. HTTP request is sent to that address requesting information
  3. '200 OK' message is sent by server if request is approved, and server sends the website's file to the browser through data packets
  4. browser parses the files and renders them as a web page

- order component files are parsed
  1. HTML
  2. CSS and JS
  3. DOM tree is created from parsed HTML, CSSOM from parsed CSS, and then  compiles/executes parse JS
  4. users sees the visual representation of the code
  
  
### Javascript basics
- JavaScript is a programming language that adds interactivity to a website
- used with web browser APIs, third-party APIs, and third-party frameworks

### Links for this Section

## Introduction to HTML

### Getting Started with HTML
- HTML is a markup language used to struchture web pages
- consists of elements used to enclose, wrap, or makr up different content
- Anatomy of an element
  1. opening tag: name of element wrapped in brackets, marks beginning of element
  2. content: what ever data you want inside the element
  3. closing tag: sam as opening tag but marks the end of an element
  ```
  <p/> this is my HTML element example <p>
  ```
- Elements can be placed inside of elements, called nesting, don't overlap opening/closing tags
- Block level elements: appears on a new line and takes up the entire width of the parent element
- Inline elements: appear on the same line within the parent and only take up the width of that element
- Attributes contain extra information about the element, don't appear in content but help with markup</br>

- Anatomy of an HTML Document
  1. ``` <DOCTYPE htmL> ```
  2. ``` <htmL></html> ``` wraps all the content on the page, root element
  3. ``` <head></head> ``` container for things that aren't content; keywords, CSS style content, character set declarations
  4. ``` <meta charset="utf-8"> ```
  5. ``` <title></title> ``` sets the title of the page that appears on the browser tab
  6. ``` <body></body> ``` displays all content on the page; tet, images, videos, games, audio and anything else</br>

- Entity References are special codes that represent characters
``` &alt; ```
- HTML Comments
``` <!-- this is a comment that does not appear on the webpage but includes helpful information --> ```

### Document and Website Structure
- header, ``` <header></header> ``` 
- navigation bar ``` <nav></nav> ```
- main content ``` <main></main> ```
subsections can include articles, sections and divs
- sidebar ``` <aside></aside> ```
- footer ``` <footer></footer> ```



### What's in the head? Metadata in HTML
- the head contains metadata that is not displayed on the webpage
- the title goes in the head, not to be confused with h1, which goes in the body
- the metadata is data that describes data, the meta tag is HTML's way of adding metadata
- some meta elements contain name and content attributes<
- a favicon will add an icon to the link when saved as bookmark
- link and script are common in the header to include CSS and JS


### Links for this Section
[Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)
[Getting Started with HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)
[Document and Website Structure](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure)
[What's in the head? Metadat in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML)


## Miscellaneous

## Things I want to know more about
- I have much more of a coding background than a networking background. I do know that sending data back and forth is important part of being able to provide the source code and data to the user. I would like to know more about internet protocols and how requests are made and fulfilled.
- Working with API's is such an important part of web development. I would like to know about the ins and outs of how APIs work and how to use them.
