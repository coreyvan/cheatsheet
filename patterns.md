# Patterns

## Middleware pattern

Provides services in addition to what the OS provides. Often described as software glue.

In web servers we use middleware to perform functions that need to be called on many different routes.

Middleware functions are functions that have access to the request object, the response object, and the next middleware function in the application’s request-response cycle. The next middleware function is commonly denoted by a variable named next.

Use middleware for:

- Preparing requests or validating them before the business layer performs it's actions
- Authentication of all requests
- Handling CORS
- Logging
- Error handling

**Resources**

- [Middleware in Express.js](https://dzone.com/articles/understanding-middleware-pattern-in-expressjs)
- [Writing Adapters in Go](https://medium.com/@matryer/writing-middleware-in-golang-and-how-go-makes-it-so-much-fun-4375c1246e81)
