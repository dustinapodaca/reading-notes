<img src="https://members-csforall.imgix.net/members/logos/code-fellows-logo-horizontal-2-color-black.png" width="340" height="66">  

# Code 401 Reading Notes

## Class 09 Reading Notes

### ES6 Classes

```
1. Classes are a template for creating ____.
   - Classes are a template for creating objects.
2. Can a class declaration be hoisted?
   - No, class declarations are not hoisted (i.e. moved to the top of the code).
3. How would you describe a constructor and contextual “this” to a non-technical friend?
   - A constructor is a special method in a class that is used to create and initialize an object created from that class. The "this" keyword refers to the object that the constructor is creating.

```

### Using Express Routing

```
1. Within Express, what does routing refer to?
   - In the context of Express, routing refers to the process of defining and handling the different endpoints (i.e. URL paths) in an application.
2. What is the difference between a route path and a route method?
   - A route path is the URL pattern that the route is associated with, while a route method is the HTTP verb (e.g. GET, POST, PUT, DELETE) that is used to access the route.
3. When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?
   - You should add the `next` parameter to a route handler when you want to pass control to the next middleware function in the stack. If `next` has been passed to your middleware as a parameter, you should call it to pass control to the next middleware function.
```

### Express Routing

```
1. What is an Express Router?
   - An Express Router is an isolated instance of middleware and routes that can be mounted on an Express app.
2. By what mean do we initialize express.Router() in an express server?
   - To initialize an Express Router in an Express server, you can use the `express.Router()` method.
3. What do we use route middleware for?
   - Route middleware is used to perform tasks such as validating input, authenticating users, or checking for permissions before a request is handled by a route handler.
```
