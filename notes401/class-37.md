# Redux - Combined Reducers

## Multiple Reducers Example
1. Why create multiple reducers?
- Having one large reducer function that changes many different parts of the state would be hard to debug and maintain 

2. How would you combine multiple reducers?
- create separate reducer functions for each part of the state
- use the combineReducer function from redux, and pass all the reducers as a parameter
```js
import { combineReducers } from 'redux';
const reducers = combineReducers({
  usersReducer,
  tweetsReducer
})
```

3. How will you manage state as an immutable object? why?
- override the current state object and create a new one with destructuring every time
```js
state = {...state, name: action.payload }
```

## Redux Docs: Using Combined Reducers
1. combineReducers is a utility function to simplify the most common use case when writing ___ _____ .
- redux reducers

2. Explain how combineReducers assembles the new state tree.
- combineReducers calls each slice reducer with its current slice of state and current action

3. How would you define initial state in an app using combineReducers?
- the createStore function can take preloaded state as its second argument
- the root reducer can return initial state when the state argument is undefined

## Redux Docs: Combined Reducer Syntax
1. Why will you want to split your reducing functions as your app becomes more complex?
- it will allow you to manage independent parts of state

2. The _____ helper function turns an object whose values are different reducing functions into a single reducing function you can pass to ____.
- combineReducers
- createStore

3. What is a popular convention when naming reducers?
- to name reducers after the state slices they manage so they can use ES6 property shorthand notation

### Links
[Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE)

[Redux Docs: Using Combined Reducers](https://redux.js.org/usage/structuring-reducers/using-combinereducers/)

[Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/)