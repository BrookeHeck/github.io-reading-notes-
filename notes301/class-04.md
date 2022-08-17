# React and Forms

## Summary
Handling user input with forms is different from handling them with normal HTML. In React, we have controlled components, which means they update the state of a component every single time the user enters something into an input field.

The ternary operator is a nice little short hand for shortening conditionals. Instead of an if else statement, you can put it all on one line.

## React Docs - Forms
1. What is a ‘Controlled Component’?

      A controlled component is a React component that renders a form and also controls what happens in that form when the user enters input.

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

    The value that user inputs should be set to the state value every single time the user changes input so that the value can be passed to other UI elements.

3. How do we target what the user is entering if we have an event handler on an input field?

    The input should have an onChange listener.
    ```
    <input type="text" value={this.state.value} onChange={this.handleChange} />
    ```

## The Conditional (Ternary) Operator Explained
1. Why would we use a ternary operator?

    A ternary operator is helpful when you have a conditional that can fit on one line. Instead of writing an if else statement, the ternary is a shorthand that shortens up the code.

2. Rewrite the following statement using a ternary statement:
``` 
if(x===y){
  console.log(true);
} else {
  console.log(false);
}
```

 ``` 
 x === y ? console.log(true) : console.log(false) 
 ```

## Things I want to learn more about
- What does this.handleChange.bind(this) doing in the event handlers for the form examples?

### Links
[Forms](https://reactjs.org/docs/forms.html)

[The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

[Forms](https://react-bootstrap.github.io/forms/overview/)

[Conditional Rendering](https://reactjs.org/docs/conditional-rendering.html)