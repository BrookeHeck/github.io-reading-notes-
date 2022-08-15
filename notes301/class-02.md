# State and Props

## Summary
The first article goes over the three major lifecycle phases of a React component. These would be mounting, updating, and unmounting. There are multiple methods that can be called in each phase. For example the constructor, render, and componentDidMount methods are all called during mounting. There are also a number of methods that can be called when states change within a component, and finally for unmounting, which removes the component from the DOM.

The video talked specifically about the difference between props and states. Props act like arguments that are passed into a function. States are more like fields within an object. Props can be passed to components, and then components can update based on the prop.

## React Lifecycle
1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

    'render' occurs before 'componentDidMount'

2. What is the very first thing to happen in the lifecycle of React?

  Mounting, but more specifically, 'Constructor'

3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

    constructor, render, componentDidMount, React Updates, componentWillUnmount

4. What does componentDidMount do?

    componentDidMount is used to load anything using a network request or initialize the DOM. This is also a good place for subscriptions.

## React State and Props
1. What types of things can you pass in the props?

    Props are used to pass any type of data to the component. This is similar to passing arguments into a function.

2. What is the big difference between props and state?

      The main difference is that props are passed to the component and state is something within the component. Props could be passed to a component to update the state within that component.

3. When do we re-render our application?

    When the state changes within a component, the application is re-rendered. Props are changed outside of the component and will not rerender the application.

4. What are some examples of things that we could store in state?

    States are helpful for data that changes based on what the user has done. An example of this could be a shopping cart. When a user adds an item, the shopping cart component would change the state, or the number of items in the cart, and the application would rerender to show this.

## Things I want to know more about
- I want to dig deeper into the architecture of React. It sounds like components are instances of classes, states are fields, and props are arguments passed into methods. Is this actually what is happening behind the scenes or is it something completely different.

### Links 
[React: Component Lifecycle Events](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

[React State vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

[State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)

[Handling Events](https://reactjs.org/docs/handling-events.html)

[Tutorial: Intro to React](https://reactjs.org/tutorial/tutorial.html)

[React Bootstrap](https://react-bootstrap.github.io/)

[Bootstrap Cheatsheet](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)

(All Bootstrap CSS classes)[https://bootstrapshuffle.com/classes]

(Netlify)[https://www.netlify.com/]