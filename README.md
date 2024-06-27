4. How do var, let, and const differ in terms of scope?
 Scope: Variables declared with var have function scope or global scope (if declared outside any function)
 variables declared with let have block scope, which means they are only accessible within the nearest curly braces { } where they are defined.
 Constants declared with const also have block scope, similar to let.


5. What are the implications of declaring a variable without any keyword (i.e., no var, let, or const)?
 this leads to unintended global variables increasing the risk of bugs and poor performance.


6. What is the scope chain, and how does JavaScript use it to resolve variable access?
 The scope chain is like a map that JavaScript follows to find variables in your code. By organizing your variables into the right scopes (functions, blocks), you make sure JavaScript can find and use them correctly wherever they’re needed. This makes your code more predictable and easier to maintain as it grows.


7. What are some differences between lexical scope and dynamic scope? Which one does JavaScript use?
  Lexical scope means that the scope of a variable is determined by its position within the source code. This approach is straightforward and predictable, contrasting with dynamic scope, which relies on the runtime call stack. JavaScript's use of lexical scope helps developers write cleaner, more organized code and facilitates easier maintenance and debugging.



8. What is a closure, and how does it relate to scope in JavaScript?
 A closure is a function that retains access to its lexical scope allowing it to access and manipulate variables from that scope even after the scope has finished executing. Understanding closures and how they relate to scope is crucial for writing efficient and flexible JavaScript code, especially in scenarios involving callbacks, event handlers, and maintaining data privacy.