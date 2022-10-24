# Component Based UI

## react hello world
1. What is the difference between an element and a React component?
- component is a reusable building block of a UI
- react element is something that describes DOM nodes and properties

2. What are some advantages of React’s component based architecture?
- Components have the functionality of JavaScript, but are virtual representations of what appears on the UI
- Components are reusable

## introducing jsx
1. What is JSX and why do we use it?
- JSX is an extension to JavaScript, it is used with React to describe what the UI should look like
- it looks like template language, but is really JS
- we use JSX because it is a helpful visual aid when working with UI inside JS code

2. Describe the process of embedding JavaScript expressions in JSX.
- declare an element, and then you can put any valid js expression inside curly brackets within the element
```js
const name = 'Josh Perez';
const element = <h1>Hello, {name}</h1>;
```

3. Is it safe to embed user input in JSX? Explain.
- Yes, React DOM escapes any values embedded in JSX before rendering them

## rendering elements
1. Explain what a React Component is to a non-technical friend.
- React components let you split the UI into independent and reusable pieces. It is like building a template of a house in a subdivision. A contractor will make a template for a house, and then when they want to build another house in the subdivision, they can reuse that template.

2. Describe mutability and React Components, specifically, how is the UI updated?
- React elements are immutable
- React DOM compares the element and its children to the previous one and only updates the DOM where necessary

3. If changes are made to the UI, what does React update?
- ONly the text node whose contents have changed get updated by React DOM

### Links 
[react hello world](https://reactjs.org/docs/hello-world.html)

[introducing jsx](https://reactjs.org/docs/introducing-jsx.html)

[rendering elements](https://reactjs.org/docs/rendering-elements.html)

[sass cheatsheet](https://devhints.io/sass)

[react cheatsheet](https://devhints.io/react)

[another react cheatsheet](https://reactcheatsheet.com/)