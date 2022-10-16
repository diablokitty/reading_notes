# Reading Notes for Day 6 of 401:

## Securing Passwords

- Explain to a non-technical friend how you would safely hash and store a password. 

When you store a password you want to make sure that it's not easy for someone to look into the database and get that information you scramble it and store it that way, but you need a way to unscramble it. That's what hashing is. 

- What is Bcrypt? 
A library that encrypts passwords using hashing methods.

- Why might you use something like Bcrypt?

It's easier to to use an existing library than to write all of that code on your own. 

## Basic Auth

- What is Basic Authentication? 
Using a string to authenticate a password instead of a token.

- What properties are necessary in the header of a Basic Auth request?


- How are username:password in Basic Auth encoded?

## OWASP auth cheatsheet

- Define the authentication process to a non-technical recruiter.
- How should your error messaging respond (both HTTP and HTML)? Why?


### Bookmark this link also and consider OWASP fundamentals any time you interact with authentication. Applications developed with security in mind from inception have fewer vulnerabilities throughout their lifecycle.

Bookmark and Review

[bcrypt docs](https://www.npmjs.com/package/bcrypt)

### Things I want to know more about:

[back to Table of Contents](./README.md)
