
# Functions in JavaScript

### 5.1 Function Declarations and Expressions

Functions in JavaScript can be defined using declarations or expressions. A function declaration, like `function greet(name)`, declares a named function and hoists it, meaning it can be called before its declaration in the code. A function expression, on the other hand, involves creating a function and assigning it to a variable, typically an anonymous function. This approach doesn't hoist the function, so it must be defined before it is used.

Code Example:
```js
function greet(name) {
  return "Hello, " + name + "!";
}
```

### 5.2 Function Parameters and Arguments

In JavaScript, function parameters are the named variables listed in the function definition, serving as placeholders for the values the function will operate on. Arguments, on the other hand, are the actual values passed to the function when it is invoked. These values are mapped to the function's parameters in the order they are passed.

Code Example:
```js
function add(x, y) {
  return x + y;
}
```

### 5.3 Function Scope, Closures, and Lexical Scoping

Function scope in JavaScript refers to the visibility and lifetime of variables defined within a function. Variables declared within a function are local to that function and cannot be accessed outside of it. Closures are a powerful feature where a function retains access to the scope in which it was created, even after that scope has closed. Lexical scoping means that the accessibility of variables is determined by their physical location in the written code.

Code Example:
```js
function outer() {
  let outerVar = "I am outer!";
  function inner() {
    console.log(outerVar); // Accesses outerVar from its parent function's scope
  }
  return inner;
}
```

### 5.4 Recursion and Tail Recursion

Recursion in JavaScript is a programming technique where a function calls itself in order to solve a problem. It’s commonly used in scenarios where a problem can be divided into similar sub-problems. Tail recursion is a specific form of recursion where the recursive call is the last operation in the function. This can be optimized by some compilers to improve performance and stack usage.

Code Example:
```js
function factorial(n) {
  if (n <= 1) {
    return 1;
  }
  return n * factorial(n - 1);
}
```

### 5.5 Higher-Order Functions and Callbacks

Higher-order functions are functions that take other functions as arguments or return them as results. This concept is a key part of functional programming in JavaScript. Callbacks are functions passed as arguments to another function. These are typically used to handle asynchronous operations or to customize the behavior of a function.

Code Example:
```js
function doMath(operation, x, y) {
  return operation(x, y);
}
```
