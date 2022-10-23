# Component Based UI

## react hello world
1. What are the building blocks of a React app?
- 

2. What is the difference between an element and a React component?

3. What are some advantages of React’s component based architecture?

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

2. Describe mutability and React Components, specifically, how is the UI updated?

3. If changes are made to the UI, what does React update?

### Links 
[react hello world](https://reactjs.org/docs/hello-world.html)

[introducing jsx](https://reactjs.org/docs/introducing-jsx.html)

[rendering elements](https://reactjs.org/docs/rendering-elements.html)

[sass cheatsheet](https://devhints.io/sass)

[react cheatsheet](https://devhints.io/react)

[another react cheatsheet](https://reactcheatsheet.com/)