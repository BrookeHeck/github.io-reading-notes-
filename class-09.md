# Forms and JS Events

## Summary
The readings introduced HTML forms. This is a super important part of making interactive websites. Forms help servers collect data from a user, and that makes many of the things we use websites for possible. Being able to store and retrieve data based on user inputs has greatly increased the different ways we use the internet.
\
Event handlers can be used for many things, and being able to submit HTML forms is just one example. Event listener methods are invoked on element objects, and they are passed the event that signals the code to execute and the function with the code that will execute. Being able to write code based on what the user wants makes website way more interactive and useful.

## HTML Forms
1. Why are forms so important in web development?
- JS forms allow us to handle data that is input by a user. This is super important for web development because not only can we personalize web applications for a user, but we can use forms to provide data to other servers. This means a user can make a specific request to a server, or they can send their own data to a server. This makes everything from online shopping to the cloud possible.

2. When designing a form, what are some key things to keep in mind when it comes to user experience?
- Keep it simple. Large forms that require a lot of user input requiring specific formats may frustrate a user.
- Structure the form from a user point-of-view.

3. List 5 form elements and explain their importance.
- The form element wraps all other elements of the form.
- The label element corresponds with an input and lets the user know what they should enter in the input field.
- The input element is a single line of text input. You can specify the type of input to help with formatting and validation. For example, an input of type email only accepts email addresses
- The button element allows the form to be submitted to a web server defined in the action attribute.
- The textarea element allows the user to enter multiple lines of data. This could be useful for a comment section or something that requires an explaination. 

## JS Events
1. How would you describe events to a non-technical friend?
- Event listeners tell your code how to react based upon a user input. Common ones are click and hover, but there are many more. This makes websites super interactive because the application will react to what the user is doing.

2. When using the addEventListener() method, what 2 arguments will you need to provide?
- The event listener method needs to be passed the event that signals the code to run, and a function with the code that will execute on that signal.

3. Describe the event object. Why is the target within the event object useful?
- The event object is a parameter passed to an event handler function. The event object is the object that the event listener function is evoked on, and the object is automatically passed to the event hanlder function. This could be useful to pass information about the object to be used in the function.

4. What is the difference between event bubbling and event capturing?
- Event capturing is when the parent element is used to listen and handle events. This works because the child is nested within the parent, so for a user to click the child they are also clicking the parent.
- Event bubbling is when an event listener is added to the child and the parent. When the child is clicked, both events fire. It's called bubbling because the child event will fire first and then work it's way out to the outermost element with an event handler.

## Things I want to learn more about
- Click and hover are two very common event listeners, but there are so many more. I would like learn more in depth about the different event listeners.

### Links
[HTML Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)
\
[Your First Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms)
\
[How to Structure A Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)
\
[Introduction to Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)
\
[HTML input types](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)
\
[Event reference](https://developer.mozilla.org/en-US/docs/Web/Events)
