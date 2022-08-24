# Reading Notes for Day 8 of 301:

## Readings: APIs

### [Reading API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

- What does REST stand for?

  Representational State Transfer

- REST APIs are designed around a ____.

  Resource. That would be an object, data or service that can be accessed by the client. 

- What is an identifier of a resource? Give an example.

  It would be a URI that allows the client to find the resource, for example:

  https://great-food.com/recipies/meatballs_1 might give the client access to the first meatball recipe in the api. And now I'm hungry for Italian.

- What are the most common HTTP verbs?

  GET, POST, PUT PATCH and DELETE

- What should the URIs be based on?

The resource and not operations on the resource.

- Give an example of a good URI.

prettythings/dresses

- What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

API's that send back a lot of small responses, and no, they take up too many resources. Best to info dump and let the client sort it out. 

- What status code does a successful GET request return?

200

- What status code does an unsuccessful GET request return?

204

- What status code does a successful POST request return?

201

- What status code does a successful DELETE request return?

204

### Bookmark and Review
[RegExr](https://regexr.com/) - Pay particular attention to the cheatsheet
[Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)
[Regex 101](https://regex101.com/)



## Things I want to know more about:

There's just a lot here. I am scratching the surface of RESTFul design. Turns out it has nothing to do with good visuals.

