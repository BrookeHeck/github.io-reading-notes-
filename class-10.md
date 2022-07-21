# Debugging

## Summary
Today's reading was all about debugging JavaScript code. Debugging can be a frustrating part of coding, so learning about tools that can help with this is great. IDEs and console messages are helpful for debugging syntax errors, and are generally easy fixes. Logic errors can be incredibly frustrating and depending on how complex the code is, can take hours. Setting a breakpoint and walking through the code line by line is super helpful when trying to see logic errors.

## Troubleshooting JavaScript
1. Name some key differences between a Syntax Error and a Logic Error.
- Syntax errors are spelling errors that cause the program to not work because they don't conform to the rules of the language.
- Logic errors may run and execute, but don't give the correct results. These are harder to fix becuase there are no error messages and the error is in the structure of the code.

2. List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.
- One logic error that happened was in lab seven when I was trying to add the global hourly totals at the bottom of the table. I had a for loop and a nested for loop, but forgot to zero out the total after my nested loop finished. I ended up with the total from all the stores for the entire day.
- A syntax error that occured was I had a lot of nested conditionals and I ended up with an extra curly brace.

3. How will this topic continue to influence your long term goals?
- Debugging is a skill that can substantially effect the time it takes to create an application. It is an important skill to practice so I don't spend hours trying to fix one small bug when I could be working on furthering the completion of the app.

## The JavaScript Debugger
1. How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?
- The debugger tool allows you to pause code execution at a specific point in order to figure out what is happening at that moment. This is super helpful for a logic error. I think I use it most often when I am using loops. It is nice to pause a loop and see what is happening through each iteration.

2. Define what a breakpoint is.
- A breakpoint is a specified spot in the code that a debugger will stop execution. From there you are able to go through each line indiviually and see how your variables are changing.

3. What is the call stack?
- The call stack shows which code was executed before the current line of code. This can be helpful when you make function calls inside of functions. The call stack shows which functions were called to get to that point.

## Things I want to learn more about

### Links
[What went wrong? Troubleshooting JavaScript](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools#the_javascript_debugger)
\
[The JavaScript Debugger](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools#the_javascript_debugger)
\
[Debugging HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Debugging_HTML)
\
[Debugging CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Debugging_CSS)