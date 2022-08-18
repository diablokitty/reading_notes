# Reading Notes for Day 3 of 301:

##Readings: Passing Functions as Props

### Reading [React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

- What does .map() return?

A new array based on the information in the passed in array and whatever machinations the programmer has gotten up to.

- If I want to loop through an array and display each value in JSX, how do I do that in React?

  Using forEach or map, and a handy pair of curly braces.

- Each list item needs a unique ___.

Identifier. (This question is badly written. The identifier only needs to be locally unique, within the object.)

- What is the purpose of a key?

See the question above? The key is that unique identifier the list items need.

### Reading [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

- What is the spread operator?

A nifty shortcut for manipulating arrays.

- List 4 things that the spread operator can do.

Add an item to an array, combine an array, use a math function, add a state in React.

- Give an example of using the spread operator to combine two arrays.

let arr =[1,2]
let arr2=['a','b']
let combinedArr = [...arr,...arr2]

The result will be combinedArr = [1,2,'a','b']


- Give an example of using the spread operator to add a new item to an array.

The fruit example in the article is hard to read, and why does he use all these emojis?

From the reading:
'console.log(...[...fruits,'...',...moreFruits]) //  🍑 🍊 🍌 🍉 🍍 ... 🍏 🍊 🍌 🍉 🍍'
I'm not really sure if his last three dots are a code example or an ellipsis. Either way, this is hard to read. 

- Give an example of using the spread operator to combine two objects into one.

It's pretty much exactly like combining arrays, except with curly braces instead of brackets.

### Videos [How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

- In the video, what is the first step that the developer does to pass functions between components?

I wasn't paying that much attention, but if he doesn't import the components into each other, he's going to be screwed.

- In your own words, what does the increment function do?

It add to the count of a person object.

- How can you pass a method from a parent component into a child component?

Props does that.

- How does the child component invoke a method that was passed to it from a parent component?

It calls a method that was passed from the parent like a prop (passing any needed arguments) and the returned argument can affect the state of the parent element.

### Bookmark and Review
[React Tutorial through ‘Declaring a Winner’](https://reactjs.org/tutorial/tutorial.html)
[React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)

## Things I want to know more about:

I am going to look for a better article on the Spread Operator, because that one was difficult to read and all those emojis were affecting my tranquility. I also think I need to watch the video on state again, because that guy does stuff really fast, and I probably need to try pausing the video and coding along or something similar. I mean, I get that we're calling a state function of a parent element in the child element, but it feels like there might be some limitations to this. 
