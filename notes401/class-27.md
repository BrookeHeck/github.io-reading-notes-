# useState() Hook

## Introducing Hooks
1. What was the motivation for introducing Hooks?
- Hooks allow you to reuse stateful logic and behavior without changing component hierarchy
- hooks can be shared among many components

2. What changes are important regarding implementing Hooks versus Component Classes?
- you don't need to bind event handlers using this

3. Hooks allow you to reuse stateful logic without changing ___ _______.
- component hierarchy

## hooks api
1. Name two rules imposed by React Hook usage.
- only call hooks from the top level, don't nest hooks
- only call hooks from within React function components

2. How would you identify a custom Hook and why might you create one?
- A custom hook is for reusing the same stateful logic between components
- You create one by making a function that doesn't return any React components, but use useEffect or useState
- Convention for naming custom hooks is to always start the name with use

## the state hook
1. What is a Hook?
- a function that lets you 'hook into' react features and lifecycle.

2. When would I use the useState Hook?
- If you have some temporary data that needs to be used and changed within a React component or used by a component's children

3. If you were to add React state to a function component by declaring a state variable:
    1. What does calling useState do?
    - declares a 'state variable'

    2. What do we pass to useState as an argument?
    - the initial state

    3. What does useState return?
    - a pair of values, the current state and a function to update the state

### Links
[Introducing Hooks](https://reactjs.org/docs/hooks-overview.html)

[hooks api](https://reactjs.org/docs/hooks-overview.html)

[the state hook](https://reactjs.org/docs/hooks-state.html)

[hooks api reference](https://reactjs.org/docs/hooks-reference.html)
