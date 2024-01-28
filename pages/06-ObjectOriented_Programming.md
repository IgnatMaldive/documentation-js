
# Object-Oriented Programming in JavaScript

### 6.1 Constructor Functions and Classes

Constructor functions and classes are fundamental in JavaScript for creating objects. Constructor functions provide a way to create objects and initialize properties. ES6 introduced 'class' syntax, which offers a cleaner and more intuitive way to create these functions and handle inheritance. The example demonstrates a constructor function to create a new 'Person' object.

Code Example:
```js
function Person(firstName, lastName) {
  this.firstName = firstName;
  this.lastName = lastName;
}
const person = new Person("John", "Doe");
```

### 6.2 Inheritance and Prototypal Chain

In JavaScript, inheritance is achieved through the prototypal chain, a mechanism where objects can inherit properties and methods from other objects. Understanding this is key to effective object-oriented programming in JavaScript. The example illustrates a basic inheritance scenario using the 'Animal' function constructor and adding a method to its prototype.

Code Example:
```js
function Animal(name) {
  this.name = name;
}
Animal.prototype.speak = function() {
  console.log(this.name + " makes a sound.");
};
```

### 6.3 Encapsulation and Data Hiding

Encapsulation and data hiding are important principles in object-oriented programming, allowing objects to hide their internal state and expose only necessary parts. In JavaScript, this can be achieved using closures and more recently, with ES6 classes. The example shows how to create a class with private data and expose a public method to access it.

Code Example:
```js
class BankAccount {
  constructor(balance) {
    let _balance = balance;
    this.getBalance = function() {
      return _balance;
    };
  }
}
```

### 6.4 Polymorphism and Method Overriding

Polymorphism allows objects of different classes to be treated as objects of a common super class. It’s closely related to method overriding, where a subclass redefines a method of its superclass. This enables flexibility and more dynamic behaviors in object hierarchies. The example illustrates method overriding in a 'Shape' class hierarchy.

Code Example:
```js
class Shape {
  area() {
    // Base class implementation
  }
}
class Circle extends Shape {
  area() {
    // Circle-specific implementation
  }
}
```
