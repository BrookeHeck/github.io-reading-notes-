# Passing Functions as Props

## Summary

## React Docs - lists and keys
1. What does .map() return?

    Map returns an array. It will loop through an array, execute a callback function for each iteration. Whatever the callback function returns will be added to a new array, and that new array is what is returned.

2. If I want to loop through an array and display each value in JSX, how do I do that in React?

    It is the same concept and syntax but the code must be inside of curly braces.

3. Each list item needs a unique ____.

    Key

4. What is the purpose of a key?

    Keys are used for extracting components. They serve as an ID for a specific component.

## The Spread Operator
1. What is the spread operator?

    The spread syntax is used to make elements of an array into individual arguments.

2. List 4 things that the spread operator can do.

    The spread operator is useful for copying an array, combining arrays, using array elements in math functions, using an array as an argument, adding to state in react, or converting a NodeList into an array

3. Give an example of using the spread operator to combine two arrays.
    ```
    arr1 = [1, 2, 3, 4, 5];
    arr2 = [6, 7, 8, 9, 10];

    let combine = (arr1, arr2) => [...arr1] + [...arr2];

    console.log(combine(arr1, arr2));
    ```
    Output
    ```
    1,2,3,4,5,6,7,8,9,10
    ```

4. Give an example of using the spread operator to add a new item to an array.
    ```
    arr1 = [1, 2, 3, 4, 5];
    arr2 = [7, 8, 9, 10];

    let combine = (arr1, arr2) => [...arr1, 6, ...arr2];

    console.log(combine(arr1, arr2));
    ```
    Output
    ```
    [1, 2, 3, 4,  5, 6, 7, 8, 9, 10]
    ```

5. Give an example of using the spread operator to combine two objects into one.

    ```
    obj1 = { first: 'Brooke' };
    obj2 = { last: 'Heck' };

    let combine = (obj1, obj2) => {
    return { ...obj1, ...obj2 }
    };
    console.log(combine(obj1, obj2));
    ```
    Output
    ```
    { first: 'Brooke', last: 'Heck'}

## How to Pass Functions Between Components
1. In the video, what is the first step that the developer does to pass functions between components?

2. In your own words, what does the increment function do?

3. How can you pass a method from a parent component into a child component?

5. How does the child component invoke a method that was passed to it from a parent component?

## Things I want to learn more about

### Links
[Lists and Keys](https://reactjs.org/docs/lists-and-keys.html)

[How to Use the Spread Operator (…) in JavaScript](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

[React - How to Pass Functions between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

[Tutorial: Intro to React](https://reactjs.org/tutorial/tutorial.html)

[Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)