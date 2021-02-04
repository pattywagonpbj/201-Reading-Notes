# Error Handling & Debugging

- To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run. (JS Book, page 452-453)
- The JavaScript interpreter uses the concept of execution contexts. There is one global exevution conctext; plus, each function creates a new new execution context. They correspond to variable scope.

- **The Stack**: The JavaScript interpreter processes one line of code at a time. When a statement needs data from another function, it stacks (or piles) the new function on top of the current task.(JS book, pg 454)

## How to deal with errors (JS book, pg 462)
1. Debug the script to fix errors.
2. Handle errors gracefully

## A Debugging Workflow
- Debugging is about deduction; eliminating potential causes of an error.

## Browser DEV tools & JavaScript Console

- The JavaScript console will tell you when there is a problem with a script, where to look for the problem and what kind of issue it seems to be. 

### Breakpoints

- You can pause the execution of a script on any line using breakpoints. then you can check the values stored in variables at that point in time. 

### Stepping through code

-If yhou set multiple breakpoints, you can step through them one-by-one to see where values change and a problem might occur. 
