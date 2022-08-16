# Reading Notes for Day 2 of 301:

## Readings: State and Props

### Reading [React lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

Render.

- What is the very first thing to happen in the lifecycle of React?

Constructor.

- Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates

constructor, render, componentDidMount, React Updates, componentWillUnmount

What does componentDidMount do?

It's a method used to load things using a network request or for initializing the DOM.

### Videos [React State Vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

- What types of things can you pass in the props?

Anything you want to pass into a function as an argument. This includes context for renders.

- What is the big difference between props and state?

Props are passed into a component and are updated outside of the component and state is resident inside the component and is updated inside the component.

- When do we re-render our application?

When our state changes.

- What are some examples of things that we could store in state?

A counter or information a user inputs like form elements.

### Bookmark and Review
[React Docs - State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)
[React Docs - handling events](https://reactjs.org/docs/handling-events.html)
[React Tutorial through ‘Developer Tools’](https://reactjs.org/tutorial/tutorial.html)
[React Bootstrap Documentation](https://react-bootstrap.github.io/)
[Boootstrap Cheatsheet](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)
[Bootstrap Shuffle - a class “sandbox”](https://bootstrapshuffle.com/classes)
[Netlify](https://www.netlify.com/)

## Things I want to know more about:

I need to practice with state vs props. It feels like state in one component could be equal to props in another component, but I'm not sure from the video if updating the state of component a would cause a re-rended in component b. It feels like the change in information should trigger one.