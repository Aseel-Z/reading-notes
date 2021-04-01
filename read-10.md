# Call stack
- > A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function, etc.

- > In summary, then, we start with an empty Call Stack. Whenever we invoke a function, it is automatically added to the Call Stack. Once the function has executed all of its code, it is automatically removed from the Call Stack. Ultimately, the Stack is empty again.

- > Example:
function greeting() {
   // [1] Some code here
   sayHi();
   // [2] Some code here
}
function sayHi() {
   return "Hi!";
}

// Invoke the `greeting` function
greeting();

// [3] Some code here

- resource: https://developer.mozilla.org/en-US/docs/Glossary/Call_stack

# The JavaScript Call Stack 
-  call stack is synchronous; single threaded
- this is why It is important to understand  Call Stack when adopting Asynchronous

### How does it work?

- > A function invocation creates a stack frame that occupies a temporary memory.
- > It works as a LIFO — Last In, First Out data structure.