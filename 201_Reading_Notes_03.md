# Reading Notes for Day 3 of 201:

- Reading Learn HTML
Ordered and Unordered lists.

When should you use an unordered list in your HTML document?

When you have a series of related items that don't have a particular order.

How do you change the bullet style of unordered list items?

Use the "type" element.

When should you use an ordered list vs an unorder list in your HTML document?

This is kind of the same as the first question. Ordered is for when you need to list items in a particular order, unordered is for related but not in a particular order. So a grocery list vs instructions on how to diffuse a bomb.

Describe two ways you can change the numbers on list items provided by an ordered list?

I think this question is asking about using 'type' which changes the font of the numbers in an ol, vs using 'start' which changes the number at which an ol starts from one to a specified number.

There is also 'reversed' which will allow you to decrement an ol.

Learn CSS
The Box Model.

Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

Margin is the space between the skin of the box (the border) and the rest of the items on the page and padding is the space between the contents of the box and the skin of the box.

List and describe the four parts of an HTML elements box as referred to by the box model.

Margin, border, padding, contents

Learn JS
Arrays. Operators and Expressions. Conditionals. Loops.

What data types can you store inside of an Array?

You can store strings, numbers, booleans, and other arrays.

Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?


 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

This is an array of arrays. It is a valid array and you can access an item inside an array that,s inside another array by chaining two sets of square brackets together, kind of like giving an apartment number inside a building.

List five shorthand operators for assignment in javascript and describe what they do.

Assignment x = f() means	x = f()
Addition assignment	x += f() means x = x + f() (If you want to add one, you can just use x++)
Subtraction assignment	x -= f() means	x = x - f()
Multiplication assignment	x *= f() means	x = x * f()
Division assignment	x /= f() means	x = x / f()
Remainder assignment	x %= f()	means x = x % f() (This is generally called a modulo operator.)

Read the code below and evaluate the last expression and explain what the result would be and why.

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;

 This will give you nothing because these are different variable types and the answer would be nonsense.


Describe a real world example of when a conditional statement should be used in a JavaScript program.

You are trying to sort people by whether or not they have a particular disease. You would ask them a yes or no question, and perhaps have a conditional to ask addtional questions, or end their participation in a survey depending on their answer.

Give an example of when a Loop is useful in JavaScript.

When you want to run a piece of code a certain number of times. For example, you are collecting information on pets. You ask first how many pets a user has, then you run the block of code that collects name, type of pet, etc, that number of times.

## Things I want to know more about

I always have trouble with arrays, so I will definitely need to re-read that section and then do some practice work calling and manipulating arrays. 

[back to Table of Contents](./README.md)
