# Reading Notes for Day 5 of 301:

## Readings: Putting it all together (End of Week 1, Whew!)

### Reading [React Docs - Thinking in React]()

- What is the single responsibility principle and how does it apply to components?

The single responsibility principle is the idea that code should be compartmentalized into using that only do one thing, and for components they should only do one thing, and that if they grow into more than one thing, they should be split into multiple components.

- What does it mean to build a ‘static’ version of your application?

A static version of a sight is a version with no interactivity. So you're building all of the components, but withouth the user input complexity.

- Once you have a static application, what do you need to add?

You need to add functionality that gives you the minimum viable interactive version of your site. 

- What are the three questions you can ask to determine if something is state?
 1. Is it passed in from a parent? - If yes, that's props.
 2. Does it change? - If no, that's not state.
 3. Can you compute it based on any other state or props? - This one is a bit trickier, since it could be a state dependent state...

- How can you identify where state needs to live?

Figure out the highest component that needs to reference the item.

### Reading [Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

### THE WEBSITE REFERENCED ABOVE IS NOT RESPONDING RIGHT NOW - I WILL REVISE WHEN IT'S AVAILABLE AGAIN


- What is a “higher-order function”?

  Functions that operate on other functions, by either taking them in as arguments (and so effectively calling them to get data) or by returning them (so they are being called as a part of the function, and then the data they produce is being returned for use somewhere else).

- Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

Line 2: return m => m > n; is returning the first instance of m that is greater than n.



- Explain how either map or reduce operates, with regards to higher-order functions.

Map takes in all of the elements of an array, returns only the values that match a passed in parameter, and builds a new array based on the values returned.

### No addtional readings for today.

## Things I want to know more about:

I would like to find a more verbose example of how built in functions work, so that I can understand better how to pass in the information they need.