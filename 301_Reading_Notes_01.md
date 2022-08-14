# Reading Notes for Day 1 of 301:

## Readings: Introduction to React and Components

### [Component-Based Architecture](https://www.tutorialspoint.com/software_architecture_design/component_based_architecture.htm)

- What is a “component”?

  From the reading: 

    "A component is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.

    A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities. It has an obviously defined interface and conforms to a recommended behavior common to all components within an architecture.

    A software component can be defined as a unit of composition with a contractually specified interface and explicit context dependencies only. That is, a software component can be deployed independently and is subject to composition by third parties."

- What are the characteristics of a component?

  From the reading: 

    - Reusability − Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.

    - Replaceable − Components may be freely substituted with other similar components.

    - Not context specific − Components are designed to operate in different environments and contexts.

    - Extensible − A component can be extended from existing components to provide new behavior.

    - Encapsulated − A A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.

    - Independent − Components are designed to have minimal dependencies on other components.

  In short, components are intended to be discrete, reusable and generic. Like little empty thought bubbles of code that you fill with what you want to happen.

- What are the advantages of using component-based architecture?

  From the reading:

    - Ease of deployment − As new compatible versions become available, it is easier to replace existing versions with no impact on the other components or the system as a whole.

    - Reduced cost − The use of third-party components allows you to spread the cost of development and maintenance.

    - Ease of development − Components implement well-known interfaces to provide defined functionality, allowing development without impacting other parts of the system.

    - Reusable − The use of reusable components means that they can be used to spread the development and maintenance cost across several applications or systems.

    - Modification of technical complexity − A component modifies the complexity through the use of a component container and its services.

    - Reliability − The overall system reliability increases since the reliability of each individual component enhances the reliability of the whole system via reuse.

    - System maintenance and evolution − Easy to change and update the implementation without affecting the rest of the system.

    - Independent − Independency and flexible connectivity of components. Independent development of components by different group in parallel. Productivity for the software development and future software development.

    In short - the use of components standardizes projects, making development, deployment and maintenance easier, and less expensive. It also speeds up development time by supplying 'under the hood' components that the developer does not need to code by hand, and leverages the knowledge of the wider coding community via access to third-party components.



### [What is Props and How to Use it in React](https://itnext.io/what-is-props-and-how-to-use-it-in-react-da307f500da0#:~:text=%E2%80%9CProps%E2%80%9D%20is%20a%20special%20keyword,way%20from%20parent%20to%20child)

- What is “props” short for?

  'Props' is short for properties.

- How are props used in React?

  From the reading:
  
  "“Props” is a special keyword in React, which is being used for passing data from one component to another."
  
  Honestly it's just properties, but shortened, like someone was trying to make it sound cool.

- What is the flow of props?

  Props data flows one way from parent to child, and is read only, which means a child component should not change data coming from a parent component.

## Bookmark and Review
[React Tutorial through ‘Passing Data Through Props’](https://reactjs.org/tutorial/tutorial.html)
[React Docs - Hello world](https://reactjs.org/docs/hello-world.html)
[React Docs - Introducing JSX](https://reactjs.org/docs/introducing-jsx.html)
[React Docs - Rendering elements](https://reactjs.org/docs/rendering-elements.html)
[React Docs - Components and props](https://reactjs.org/docs/components-and-props.html)

## Things I want to know more about:

This is one of those cases where what I want to do is use these things, because then I'll have a better connection between the concept and practical application. So right now I'm reading, but I don't have enough understanding to have questions. But I am going to look at some You Tube videos of basic React projects to get me started. (And may I also say God Bless You Tube!) 