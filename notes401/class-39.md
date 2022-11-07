# Redux - Additional Topics

## Redux Toolkit
1. What concerns are addressed by Redux Toolkit?
- configuring a complicated redux store
- many packages are needed to get Redux to be useful
- requires a lot of boilerplate code

2. What does configureStore() do?
- wraps createStore to provide simplified configuration and defaults
- automatically combines slice reducers, adds redux middleware, and includes redux-thunk by default

3. How would I use createSlice()?
- createSlice accepts an object of reducer functions, a slice name, and an initial state value, and automatically generates a slice reducer with corresponding action creators and action types

## MobX
1. What is Mobx?
- a simple and scalable state management solution

2. How does MobX make it “impossible” to produce an inconsistent state?

3. How would we build a reactive user interface?

## Tutorial
1. What take-away(s) did this tutorial provide?

### Links
[Redux Toolkit (RTK)](https://redux-toolkit.js.org/introduction/getting-started)

[MobX](https://mobx.js.org/getting-started.html)

[Tutorial](https://redux-toolkit.js.org/tutorials/overview)

[Redux Toolkit (RTK)](https://redux-toolkit.js.org/)

[HookState](https://hookstate.js.org/)