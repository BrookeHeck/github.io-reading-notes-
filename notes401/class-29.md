# Advanced State with Reducers

## useReducer hook
1. Name an alternative to the useState Hook.
- the useReducer hook

2. Why might the useReducer Hook be preferable to the useState Hook?
- when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one
- Allows you to optimize performance for components that trigger deep updates because you can pass down dispatch instead of callbacks

3. What are two ways to set the initial state?
- pass the the initial state as a second argument
- pass in an init function as a third argument

## Ultimate Guide to useReducer
1. In terms of state, what does useReducer expect to receive as a parameter?
- it accepts a reducer function as its first parameter and the initial state as its second

2. What does useReducer return?
- useReducer returns an array that holds the current value and a dispatch function to which you can pass an action and later invoke it

3. Explain dispatch to a non-technical recruiter.
- the dispatch function accepts an object that represents the type of action we want to execute and when it is called
- it ends the type of action to the reducer function to perform its job
- A non-technical example of this would be like a vending machine. You push the number or letter of what you want in the vending machine, and then the vending machine will grab a snack or drink based on the input it was given

### Links
[useReducer Hook](https://reactjs.org/docs/hooks-reference.html#usereducer)

[Ultimate Guide to useReducer](https://blog.logrocket.com/react-usereducer-hook-ultimate-guide/)