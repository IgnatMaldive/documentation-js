#Control Flow in JavaScript




### 4.1 Conditional Statements (if, else, switch)

Explanation: Conditional statements in JavaScript, like 'if' and 'switch', control the flow of execution based on conditions. 'if' evaluates a condition, while 'switch' matches a value against multiple cases.
Code Example:
```js copy
let x = 10;
if (x > 5) {
  console.log("x is greater than 5");
} else {
  console.log("x is not greater than 5");
}
```




### 4.2 Loops (for, while, do-while, for&#x2026;in, for&#x2026;of)

Explanation: Loops are used to execute a block of code repeatedly. JavaScript provides several types of loops, including 'for', 'while', and 'do-while', each serving different use cases.
Code Example:
```js copy
for (let i = 0; i < 5; i++) {
  console.log(i);
}
while(x > 0) {
  console.log(x);
  x--;
}
```




### 4.3 Error Handling (try, catch, throw, custom error classes)

Explanation: Handling errors in JavaScript.
Code Example:
```js copy
try {
  // Code that may throw an error
  throw new Error("An error occurred");
} catch (error) {
  console.error(error.message);
}
```




### 4.4 Promises and Async/Await

Explanation: Asynchronous programming using Promises and async/await.
Code Example:
```js copy
function fetchData() {
  return new Promise((resolve, reject) => {
    // Asynchronous operation
    resolve("Data fetched successfully");
  });
}
```

