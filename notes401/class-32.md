# Context API - Behaviors

## Hooks and Context Example
1. With regard to the React Context API, what does a “provider” do?
- The provider gives all of its children components access to 'global' variables
- The variables don't have to be passed down as props
2. With regard to the React Context API, how would we implement a “consumer” role?
- The children must be wrapped within the provider
- The children of the provider can use the useContext hook
```js
import { useContext } from 'react';
import userInfo from 'user-provider';

function Profile() {
    const context = useContext(userInfo)

    const name = context.username;
}
```

3. Specifically with Context, how are we “wrapping” components to achieve our goals?
- A parent acts as a provider
- The parent should wrap all the components that need access to the context variables

## Awesome React Context Links
1. Consume content from (at least) two more of the Awesome React Context links. After some familiarity with React Context, once again share your takeaways from each:
    1. Takeaway 1: Context is good for a variable that is needed by many children, but use it sparingly because it can make components harder to reuse 
    2. Takeaway 2: Two examples of good places to use context is authentication variables and settings variables. These are often variables that need to be accessed by many parts of the application. It is easier to use them as context rather than pass them down to deeply nested children.

### Links
[Snackbars in React: An Exercise in Hooks and Context](https://medium.com/swlh/snackbars-in-react-an-exercise-in-hooks-and-context-299b43fd2a2b)

[awesome-react-context](https://github.com/diegohaz/awesome-react-context)