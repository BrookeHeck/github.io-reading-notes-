# Component Lifecycle / useEffect Hook

## effects hook
1. What purpose does useEffect serve in a function component compared to its counterpart(s) in class components?
- componentDidMount(), componentDidUpdate(), and componentWillUnmount()

2. When using the useEffect Hook:

    1. What does useEffect do?
    - the UseEffect hook allows for side effects in your components
    - examples are fetching data, directly updating the DOM, and timers
    - accepts a callback function and an optional dependency argument

    2. Why is useEffect called inside a component?
    - React relies on the order in which Hooks are called, all Hooks should be within a component


6. Explain the importance of properly implementing effects with Cleanup
- Sometimes you don't want cleanup because you are running code after React has updated the DOM.
  - Network requests, manual DOM manipulations, logging
- Cleanup is required to reduce memory leaks
  - timeouts, subscriptions, event listeners


### Links
[effects hook](https://reactjs.org/docs/hooks-effect.html)