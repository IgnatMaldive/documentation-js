
# Variables in JavaScript

### 2.1 Declaring and Initializing Variables

In JavaScript, variables are containers for storing data values. They are declared using `let`, `const`, or `var`. The `let` keyword allows you to declare a variable that can be reassigned later. `const` is used for declaring constants whose values cannot be changed once set. Unlike `let` and `const`, `var` has function scope and is hoisted, meaning it can be accessed before its declaration.

Code Example:
```js
let name = "John"; // A reassignable variable
const PI = 3.14; // A constant value
```

### 2.2 Data Types and Type Coercion

JavaScript is a loosely typed or a dynamic language, which means you don't need to declare a variable's type. It has several built-in data types like strings, numbers, and booleans. Type coercion refers to the automatic or implicit conversion of values from one data type to another. This occurs in contexts such as string concatenation, where JavaScript converts variables to strings if necessary.

Code Example:
```js
let age = 25;
let message = "My age is: " + age; // Type coercion converts age to a string
```

### 2.3 Variable Scope and Hoisting

Scope in JavaScript determines the accessibility of variables. Variables declared with `var` are function-scoped and are hoisted to the top of their scope, meaning they can be referenced before their declaration. However, they are initialized with `undefined`. In contrast, `let` and `const` are block-scoped and are not initialized until their declaration is evaluated.

Code Example:
```js
console.log(count); // Outputs undefined due to hoisting
var count = 10;
```

### 2.4 Variable Naming Conventions

Good variable naming is essential for readable and maintainable code. In JavaScript, it's common to use camelCase for variable names - starting with a lowercase letter and capitalizing each subsequent word. Variable names should be descriptive to indicate their purpose or the type of data they hold.

Code Example:
```js
let firstName = "John"; // Descriptive variable name in camelCase
let lastName = "Doe";   // Another example of camelCase
```

### 2.5 Constants and Immutability

The `const` keyword in JavaScript is used to declare constants - variables whose values cannot be changed once set. While the variable itself is immutable, the object it points to can still be mutable. For instance, you can't reassign a new value to a `const` variable, but if it's an object, you can change its properties.

Code Example:
```js
const PI = 3.14159; // A constant value that cannot be reassigned
```
