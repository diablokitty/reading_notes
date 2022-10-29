# Reading Notes for Day 27 of 401:

## useState() Hook

### Introducing Hooks

- What was the motivation for introducing Hooks?

Hooks solve a lot of seemingly unconnected problems in React

- What changes are important regarding implementing Hooks versus Component Classes?
Hooks let you use more of Reacts features without implementing Classes.

- Hooks allow you to reuse stateful logic without changing: 
    your component hierarchy.

### hooks api

- Name two rules imposed by React Hook usage.
  1. Only call hooks from React function components
  2. Only call hooks at the top level.

- How would you identify a custom Hook and why might you create one?
The 'use' keyword identifies custom hooks. We might create a hook when we want to reuse some stateful logic between components. 


### the state hook

- What is a Hook?
A Hook is a special function that lets you “hook into” React features.

- When would I use the useState Hook?
When we want to declare a state variable without using classes.

- If you were to add React state to a function component by declaring a state variable:
- What does calling useState do?
  It creates a stateful variable

- What do we pass to useState as an argument?
The initial state.

- What does useState return?
A pair of values: the current state and a function that updates it.

### Bookmark and Review

[hooks api reference](https://reactjs.org/docs/hooks-reference.html)

### Reflection
- What are your learning goals after reading and reviewing the class README?
I really just want to get caught up with my homework. Then I'm going to build a portfolio with React and a backend, just to solidify these skills some.

### Things I want to know more about:

Why does React have all these cutsie terms like 'props' and 'hooks'? Were the developers trying to make it fun?

[back to Table of Contents](./README.md)