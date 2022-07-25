# Reading notes for day 6 of 201

### Reading JavaScript Object Basics

1. How would you describe an object to a non-technical friend you grew up with?

  An object is like a person. It has a collection of descriptive adjectives (weight, height, hair color) and can have things it does (like blink or jump). So properties are the things an object is, and methods are what it does.

2. What are some advantages to creating object literals?

  They are used by plug-ins like JQuery and they are easy to read.

3. How do objects differ from arrays?

  Arrays don't have key value pairs. They're a collection of lists with locations assigned to them.

4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.


5. Evaluate the code below. What does the term this refer to and what is the advantage to using this?
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
 This refers the object.


### Introduction To The DOM

1. What is the DOM?

  Stands for the Document Object Model. It means the pseudo-page on which all of the code is being rendered.

2. Briefly describe the relationship between the DOM and JavaScript.

Javascript is a scripting language that can effect changes to the DOM.


### Bookmark and Review Understanding the problem domain is the hardest part of programming What’s the difference between primitive values and object references in JavaScript?




## Things I want to know more about

I'm really trying to make a conscious effort to learn to use objects effectively, so I'm trying to delve into that a bit deeper.

[back to Table of Contents](./README.md)