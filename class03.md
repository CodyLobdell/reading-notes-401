Readings


Review: ES6 Classes

Classes are a template for creating ____.
- Objects


Can a class declaration be hoisted?
- They cannot, due to temporal deadzone restrictions


How would you describe a constructor and contextual “this” to a non-technical friend?
- When we create a constructor function, we use the keyword "this" to refer to the object that is being created. It's kind of like saying "this object" or "the object we're working with right now." We can use "this" to set values for the object's properties or to define its methods (which are like functions that belong to the object)!



Using Express Routing

Within Express, what does routing refer to?
- Routing refers to how an application's endpoints (URIs) respond to client requests.


What is the difference between a route path and a route method?
- A route method is derived from one of the HTTP methods, and is attached to an instance of the express class. 
    Route paths, in combination with a request method, define the endpoints at which requests can be made.


When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?
- Adding "next" as a parameter to a route handler is a way to pass control to the next middleware or route handler function in the chain.



Express Routing

What is an Express Router?
- Express Routers are a way to organize your Express application such that your primary app. js file does not become bloated and difficult to reason about.


By what mean do we initialize express.Router() in an express server?
- The express.Router() function is used to create a new router object.


What do we use route middleware for?
- Middleware functions access the HTTP request and response objects.