#Object-Oriented Programming in JavaScript




### 6.1 Constructor Functions and Classes

Explanation: Introduction to constructor functions and ES6 classes.
Code Example:

```js copy
function Person(firstName, lastName) {
  this.firstName = firstName;
  this.lastName = lastName;
}
const person = new Person("John", "Doe");
```


### 6.2 Inheritance and Prototypal Chain

Explanation: Understanding inheritance and the prototypal chain.
Code Example:

```js copy
function Animal(name) {
  this.name = name;
}
Animal.prototype.speak = function() {
  console.log(this.name + " makes a sound.");
};
```

### 6.3 Encapsulation and Data Hiding

Explanation: Implementing encapsulation and data hiding in JavaScript.
Code Example:

```js copy
class BankAccount {
  constructor(balance) {
    let \_balance = balance;
    this.getBalance = function() {
      return \_balance;
    };
  }
}
```

### 6.4 Polymorphism and Method Overriding

Explanation: Working with polymorphism and method overriding.
Code Example:

```js copy
class Shape {
  area() {
    */ Base class implementation
  }
}
class Circle extends Shape {
  area() {
    /* Circle-specific implementation
  }
}
```
