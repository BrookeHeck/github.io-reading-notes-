# In Memory Storage

## Summary
The first article is an overview of the call stack. The stack is a last in first out data structure that is used to handle multiple function invocations. When a function is invoked, it is added to the stack. If another function is invoked inside that first invocation, this second function is added to the top of the stack. The second function is evaluated and removed from the stack first. Then the first function called is now at the top and is handled in the same fashion. Recursive functions can cause stack overflows if not used correctly. This means they have function calls occurring with no way to stop them. The browser has a maximum number of calls and will throw an error when it reaches that maximum.

The second article gives a summary of the different errors that can be thrown. This can include type errors, syntax errors, range errors, or reference errors. We can use breakpoints to help debug these errors by stopping the code before the error occurs. This is helpful because at these breakpoints we can use tools to see the values of variables at that specific time and make it easier to see why an error occurred. A debugger statement can also help with this by showing a history of what code executed before that statement.

## Understanding the JavaScript Call Stack
1. What is a ‘call’?

    A function invocation

2. How many ‘calls’ can happen at once?

    One at a time

3. What does LIFO mean?

    Last In First Out

4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

```
function add(one, two, three) {
  return one + two + three;
}

function getAverage(one, two, three) {
  return add(one, two, three) / 3
}

function printAverage(one, two, three) {
  console.log(getAverage(one, two, three));
}

printAverage(1, 8, 4);
```

5. What causes a Stack Overflow?

    A stack overflow happens when a recursion function has no statement to stop the function calls or the statement never evaluates correctly to stop the function calls. A browser has a maximum number of calls tht can be made before throwing a stack error.

## JavaScript Error Messages
1. What is a ‘reference error’?

    When you try to use a variable that is not yet declared.

2. What is a ‘syntax error’?

    A syntax error is when you have code that can't be parsed because of the syntax.

3. What is a ‘range error’?

    Range errors occur when your using an object with a length and you try to use a value outside of that length.

4. What is a ‘type error’?

    This happens when data types, like a string or number, is used incorrectly.

5. What is a breakpoint?

    A breakpoint is a specified spot in the code where execution is stopped. Then you can look at different variables in the code to see why the error might be occurring.

6. What does the word ‘debugger’ do in your code?

    A debugger statement in the code will show the history of code. This can show you what lines of code executed and what was input and returned from that code.

## Things I want to learn more about

### Links
[The JavaScript Call Stack - What It Is and Why It's Necessary](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4)

[JavaScript error messages && debugging](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

[JavaScript error reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)