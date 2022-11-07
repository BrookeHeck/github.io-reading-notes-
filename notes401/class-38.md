# Redux - Asynchronous Actions

## async actions
1. Why use Redux middleware?
- redux middleware was designed to enable writing logic that has side effects
- allows you to pass something that isn't the plain action object to dispatch as long as the middleware doesn't let that value reach the reducers
- middleware have access to dispatch and getState, you could write async logic in a middleware

2. Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.
- The flow starts by user triggering an event in
- the dispatch function is called, and the middleware catches the object passed to dispatch before it hits the reducers
- the middleware performs async logic and then passes that onto the reducers where the state is updated

3. How are we accommodating async in our Redux app?
- we accommodate async logic by using middleware
- thunk middleware is commonly used because it allows us to write functions that get dispatch and getState as arguments and then the async logic goes inside that function

## thunk middleware
1. Why would you need redux-thunk middleware?
- thunk is used to delay the reducers from updating state so that async logic can be performed

2. Redux Thunk middleware allows you to write action creators that return a ____ instead of an action.
- function to perform asynchronous dispatch

3. Describe how any return value from the inner thunk function will be made available.
- any return value from the inner function will be available as the return value of dispatch itself

### Links
[async actions](https://redux.js.org/tutorials/fundamentals/part-6-async-logic)

[thunk middleware](https://github.com/reduxjs/redux-thunk)
