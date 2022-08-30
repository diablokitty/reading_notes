# Reading Notes for Day 12 of 301:

## Readings: CRUD

### Reading [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

In your own words, describe what each group of status code represents:

100’s = These are informational only, they tell the client that the header of the request was received and the request is being parsed.  
200’s = These should be success codes, they say something was sent back (except maybe 202).
300’s = These say that the requested resources isn't available at that endpoint (any more).
400’s = These are client error codes, they say the request the client sent wasn't valid
500’s = These are server error codes, they say the server wasn't working (overwhelmed or unreachable) or that the client request wasn't sent correctly.
What is a status code 202? Asynchonous processing of a request.
What is a status code 308? Permanent redirect - points to a new good URL. Put in a change of address.
What code would you use if an update didn’t return data to a client? 204 No content found
What code would you use if a resource used to exist but no longer does? 410 Gone (but not forgotten, no also kind of forgotten.)
What is the ‘Forbidden’ status code? 403 (Like Lambada, but annoying instead of sexy.)

### Video [Build A REST API With Node.js, Express, & MongoDB - Quick - First 20 minutes](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

Why do we need to pull our MongoDB database string out of our server and put it into our .env?

To allow the server to use it as an address to locate the database.

What is middleware?

Libraries and things that do things in between two applications.

What does app.use(express.json()) do?

It allows us to use the Express library.

What does the /:id mean in a route?

means that the client may pass in a parameter we will use to evaluate what we are returning.

What is the difference between PUT and PATCH?

Patch allows for a targeted update of a key value in a record, put updates the entire record.

How do you make a default value in a schema?

add a key of default and value of whatever you want to be the default.

What does a 500 error status code mean?

Internal server error.

What is the difference between a status 200 and a status 201?

200 means the request was received, 201 means the request was successful and a resource was returned. 201 is better.

## Things I want to know more about:

I want to understand more about the relationship between the server and the database.