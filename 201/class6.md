# objects and DOM notes

## JavaScript Object Basics

How would you describe an object to a non-technical friend you grew up with?

- an object in software development is just like an object in real  life. it can be manipulated, played with, used as a container, etc

What are some advantages to creating object literals?

- flexibility and less code to declare.

How do objects differ from arrays?

- arrays are groups of values, these values can be almost anything, but at its core it is a list of stored values or data in a single variable. objects are things, usually with properties that consist of a key and a value.

Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.

- if an object property name is held in a variable it is inaccessible in dot notation, and bracket notation must be used.

Evaluate the code below. What does the term this refer to and what is the advantage to using this?

<!-- const dog = {
     name: 'Spot',
     age: 2,
     color: 'white with black spots',
     humanAge: function (){
     console.log(`${this.name} is ${this.age*7} in human years`);
  }
} -->

- .this refers to values named within that specific object. it allows values within and object like name to be called without inadverdently calling every value associated with name

## Introduction To The DOM

What is the DOM?

- DOM stands for document object model and it is the data and structure of a document on the web.

Briefly describe the relationship between the DOM and JavaScript.

- the DOM represents the document (content) of a webpage as an object. this is fantastic for programming as many languages including javascript are object based languages, which makes it easy to alter content with Javascript.

