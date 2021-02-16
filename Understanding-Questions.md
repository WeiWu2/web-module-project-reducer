# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* 
...
Step 1 - the addOne function executes, returning a object
Step 2 - The dispatch function will call the reducer function with the current state and the object that was returned from addOne
Step 3 - The reducer function will execute and returns an object with updated state
Step 4 - Finally Dispatch will set the state to the object returned from reducer


* TotalDisplay shows the total plus 1.
