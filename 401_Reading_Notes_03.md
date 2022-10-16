# Reading Notes for Day 3 of 401:

## Review: ES6 Classes

- Classes are a template for creating objects.
- Can a class declaration be hoisted? No.
- How would you describe a constructor and contextual “this” to a non-technical friend? 

## Using Express Routing

- Within Express, what does routing refer to? Routes tell the app how to handle user requests.
- What is the difference between a route path and a route method? A route path tells data where to go, and a route method tells the app what to do with the data.

- When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?

Next is used when there is middleware and when next is passed, the middleware has to be invoked so it executes.


## Express Routing

- What is an Express Router? It's a mini Express application that just routes.
- By what mean do we initialize express.Router() in an express server? We call it with a use instance.
- What do we use route middleware for? Routing things and passing errors when that doesn't work.


### Things I want to know more about:

I want to know about other types of middleware.
