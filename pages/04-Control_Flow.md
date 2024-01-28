
# Control Flow in JavaScript

### 4.1 Conditional Statements (if, else, switch)

Conditional statements in JavaScript, like 'if' and 'switch', control the flow of execution based on conditions. 'if' evaluates a condition, while 'switch' matches a value against multiple cases. These structures allow for more dynamic and responsive code that can execute different code blocks based on varying conditions. The example demonstrates an 'if-else' statement checking whether a variable `x` is greater than 5.

Code Example:
```js
let x = 10;
if (x > 5) {
  console.log("x is greater than 5");
} else {
  console.log("x is not greater than 5");
}
```

### 4.2 Loops (for, while, do-while, for…in, for…of)

Loops are used to execute a block of code repeatedly. JavaScript provides several types of loops, including 'for', 'while', and 'do-while', each serving different use cases. 'for' loops are commonly used for iterating a known number of times, while 'while' and 'do-while' loops are suitable when the number of iterations isn't known beforehand. The example shows a 'for' loop iterating a set number of times and a 'while' loop that continues as long as a condition is true.

Code Example:
```js
for (let i = 0; i < 5; i++) {
  console.log(i);
}
while(x > 0) {
  console.log(x);
  x--;
}
```

### 4.3 Error Handling (try, catch, throw, custom error classes)

Handling errors in JavaScript is crucial for robust application development. The 'try-catch' block is used to catch exceptions that may occur in a program, preventing them from crashing the application. Throwing custom errors is a way to create and manage specific error conditions. This section explains the basics of error handling using 'try', 'catch', and 'throw', along with the concept of custom error classes. The code example demonstrates throwing and catching a custom error.

Code Example:
```js
try {
  // Code that may throw an error
  throw new Error("An error occurred");
} catch (error) {
  console.error(error.message);
}
```

### 4.4 Promises and Async/Await

Asynchronous programming is a key aspect of JavaScript, especially in dealing with operations like network requests. Promises and async/await syntax offer powerful tools for handling asynchronous operations. A Promise represents a value that may be available now, in the future, or never. Async/await syntax provides a more readable way to work with promises. This section covers the basics of using promises and async/await for asynchronous operations. The example demonstrates creating and returning a promise from a function.

Code Example:
```js
function fetchData() {
  return new Promise((resolve, reject) => {
    // Asynchronous operation
    resolve("Data fetched successfully");
  });
}
```
