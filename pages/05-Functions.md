#Functions in JavaScript




### 5.1 Function Declarations and Expressions

Explanation: Functions in JavaScript can be defined using declarations or expressions. A function declaration declares a named function, while an expression assigns an anonymous function to a variable.
Code Example:
```js copy
function greet(name) {
  return "Hello, " + name + "!";
```




### 5.2 Function Parameters and Arguments

Explanation: Parameters are variables listed as part of the function's definition. Arguments are the actual values passed to the function when it is invoked.
Code Example:
```js copy
function add(x, y) {
  return x + y;
```




### 5.3 Function Scope, Closures, and Lexical Scoping

Explanation: Exploring function scope and closures.
Code Example:
```js copy
function outer() {
  let outerVar = "I am outer!";
  function inner() {
    console.log(outerVar);
  }
  return inner;
```




### 5.4 Recursion and Tail Recursion

Explanation: Introduction to recursive functions.
Code Example:
```js copy
function factorial(n) {
  if (n <= 1) {
    return 1;
  }
  return n \* factorial(n - 1);
```




### 5.5 Higher-Order Functions and Callbacks

Explanation: Working with higher-order functions and callbacks.
Code Example:
```js copy
function doMath(operation, x, y) {
  return operation(x, y);
```

