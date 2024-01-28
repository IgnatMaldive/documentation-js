
# Data Structures in JavaScript

### 3.1 Arrays: Creation, Manipulation, and Iteration

Arrays in JavaScript are used to store multiple values in a single variable. This section covers the basics of creating arrays, adding and removing elements, and iterating over array items. Common array methods like `push()` are demonstrated for manipulating array contents. The example shows how to add a new element ("yellow") to an existing array of colors.

Code Example:
```js
let colors = ["red", "green", "blue"];
colors.push("yellow");
```

### 3.2 Objects: Properties, Methods, and Prototypes

Objects in JavaScript are key-value pairs where keys are strings and values can be any data type. This section delves into creating objects, accessing their properties, and understanding the role of prototypes in JavaScript's object-oriented programming. The example illustrates creating a simple object with two properties (`firstName` and `lastName`) and accessing one of these properties using dot notation.

Code Example:
```js
let person = {
  firstName: "John",
  lastName: "Doe",
};
console.log(person.firstName); // John
```

### 3.3 Sets and Maps: Working with Unique Data

Sets and Maps are ES6 additions to JavaScript that provide ways to handle unique data and key-value pairs, respectively. A Set is a collection of unique values, while a Map holds key-value pairs with any value type. This section explains how to create and use these structures. The given example demonstrates creating a Set with numbers, automatically removing duplicate values.

Code Example:
```js
let uniqueNumbers = new Set([1, 2, 3, 1, 2]);
```

### 3.4 Working with JSON Data

JSON (JavaScript Object Notation) is a lightweight format for storing and transporting data, often used in web applications. This section covers how to parse JSON strings into JavaScript objects and stringify JavaScript objects into JSON format. The example shows parsing a JSON string representing an object with properties `name` and `age`.

Code Example:
```js
let jsonData = '{"name": "Alice", "age": 30}';
let obj = JSON.parse(jsonData);
```

### 3.5 Advanced Data Structures

Beyond basic arrays and objects, JavaScript can be used to implement more complex data structures like linked lists, trees, graphs, and more. This section provides a conceptual overview of these advanced structures, discussing their characteristics, use-cases, and basic implementation strategies in JavaScript. These structures are essential for solving more complex problems in computer science and software development.

