# Application State with Redux

## Dan Abramov Redux Tutorials
1. What is the first principle of Redux?
- represent the whole state of your application a single javascript object

2. What is a store and what do we use our reducers for within that store?
- the store is what is used to follow the three principals of redux
- it holds the current state object, it lets you dispatch actions, and when you create it you must specify the reducer
- The reducer is a function that takes in the previous state, the action, and returns the new state
- The reducer method must be a pure function, meaning it should return a copy of the object with the updated state

3. Name three Redux store methods given to us by createStore and describe their use.
- getState() - returns the current state of the store
- dispatch() - used to dispatch actions to change the state, must pass the action type in as a parameter
```js
store.dispatch({ type: 'INCREMENT' });
```
- subscribe() - lets you register a callback that will be called anytime state updates in state so that you can update the UI

4. Explain to a non-technical recruiter what combineReducers() does and why it is useful.
- combineReducer is used to help different reducers handle different actions but update only one state object

### Links
[Dan Abramov Redux Tutorials](https://egghead.io/courses/fundamentals-of-redux-course-from-dan-abramov-bd5cc867)

[worlds easiest guide to redux](https://www.freecodecamp.org/news/understanding-redux-the-worlds-easiest-guide-to-beginning-redux-c695f45546f6)

[testing reducers](https://medium.com/@netxm/testing-redux-reducers-with-jest-6653abbfe3e1)

[Redux Docs](https://redux.js.org/)