# Putting It All Together

## Summary
The first reading was very helpful because I'm just learning react. This article went through the process of determining what should be a component and what should be state. The lab directions help guide us through this process, but there isn't going to be specific directions for every application I build, so this article gave great tips on how to organize a React app and where to place state so that data flow makes sense.
The second article talked about higher order functions. forEach, map, and filter are methods that we have already used and are great examples of higher order functions. Each of these methods takes in a function as an argument so that the function can be reused many times.
>Higher-order functions allow us to abstract over actions, not just values.

## React Docs - Thinking in React
1. What is the single responsibility principle and how does it apply to components?

    The single responsibility principle is that a function or object should only do one thing. This principle can also be applied to React by making sure that components only do one thing.

2. What does it mean to build a ‘static’ version of your application?

    Building a 'static' version means getting all the components organized and rendered properly, but have no interactivity between components. This means that you don't add any state to your components.

3. Once you have a static application, what do you need to add?

    After you have built a static application, then you can add in state and functions that update state based on user input.

4. What are the three questions you can ask to determine if something is state?
    - Is it passed as a prop, then not state
    - Does it remain unchanged, not state
    - Can you compute it using other state or props, not state 

5. How can you identify where state needs to live?

    React is one directional flow of data, so state should be higher up in the hierarchy. If the state is used by multiple children, then the parent component or somewhere higher up the hierarchy should hold that state. If there isn't a single component that make sense to hold that state, you can create a parent component that houses the state.

## Higher-Order Functions
1. What is a “higher-order function”?

    These are unctions that operate on other function by taking them as arguments or returning them. Higher-order functions allow for abstraction of actions not just values.

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

    In line two, the function is returning an anonymous arrow function that accepts a number as a parameter and then compares it to the number that was passed into the greaterThan function. Returning this anonymous arrow function is how they got the greaterThan10 function.

3. Explain how either map or reduce operates, with regards to higher-order functions.

    Map and filter are two examples of higher order functions. Map takes a function as it's argument and then uses that function on every element of the array. Reusing that arrow function call passed into map or filter is what makes it a higher order function.

## Things I want to learn more about

### Links
[React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

[Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)