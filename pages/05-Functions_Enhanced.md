#Functions in JavaScript




### 5.1 Function Declarations and Expressions

Explanation: Introduction to function creation and expressions. This section covers the basics of defining functions in JavaScript, both through declarations and expressions.
Code Example:
```js copy
```js copy
function greet(name) {
  return "Hello, " + name + "!";
```

// Example of a function expression
const welcome = function(name) {
  return "Welcome, " + name + "!";
};
```

### 5.2 Function Parameters and Arguments

Explanation: Understanding function parameters and arguments. This section delves into how to pass and use parameters and arguments in functions, crucial for function versatility.
Code Example:
```js copy
```js copy
function add(x, y) {
  return x + y;
```

// Example with default parameters
function multiply(a, b = 1) {
  return a * b;
}
```

### 5.3 Function Scope, Closures, and Lexical Scoping

Explanation: Exploring function scope and closures.
Code Example:
```js copy
```js copy
function outer() {
  let outerVar = "I am outer!";
  function inner() {
    console.log(outerVar);
  }
  return inner;
```
```

### 5.4 Recursion and Tail Recursion

Explanation: Introduction to recursive functions.
Code Example:
```js copy
```js copy
function factorial(n) {
  if (n <= 1) {
    return 1;
  }
  return n \* factorial(n - 1);
```
```

### 5.5 Higher-Order Functions and Callbacks

Explanation: Working with higher-order functions and callbacks.
Code Example:
```js copy
```js copy
function doMath(operation, x, y) {
  return operation(x, y);
```
```