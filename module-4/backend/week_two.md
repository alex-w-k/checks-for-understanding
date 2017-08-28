## Week Two - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's one difference between ES5 and ES6?


ES6 allows for string interpolation.


2. What's the difference between asynchronous and synchronous JavaScript? 


Asynchronous JS does not get a response right away and is moved into the eventloop which processes after the main stack queue. Synchronous executes and gets a response right away and moves to the next part of execution.


3. What are the four pillars of Object Oriented programming?


Abstraction -- Only the essential methods/features are user facing. Everything else is abstracted away.
Inheritance -- Using class inheritance to help keep your application DRY.
Encapsulation -- Making short and sweet methods/functions to allow for reusability
Polymorphism -- Allowing multiple functions/methods to have the same name and do different things in different contexts.


4. What are some tools available in JavaScript to help you write object oriented code?

ES6 is great and allows for much more encapsulation with classes.


5. What are some key concepts to be aware of when refactoring your JavaScript?

taking any longer promices and moving them into their own function and generally breaking things out and making them more modular.


6. What's a callback function and what are some reasons when we use/need callback functions?

A callback is a function passed to another function as an argument.


7. What's the scope of variables in Javascript?

Global or Local.


8. What's the difference between `==` and `===` in JavaScript?

`==` is equal to and doesn't compare types.

`===` is equal to and exact equal to; exact equal to has to match type as well as content

9. Why do front end frameworks exist?

To make things easier and to extend what vanilla.JS can do.


#### Review  

10. Why do people say "HTTP is stateless"?

There is not a way to persist state across multiple page loads with plain HTTP

11. Describe a RESTful API.

A RESTful API is a way of organizing an API:

GET `api/$items` will have a list of all $items
GET `api/$items/:id` will show a single $item of id :id
DELETE `api/$items/:id` will delete a single $item of id :id
PATCH `api/$items/:id` will update a single $item of id :id
POST `api/$items` will create a new $item

it is used as a standard accross most APIs so data can be easily located even if it is a brand new API

12. What are some main characteristics of a team following an agile workflow?

A daily standup where you discuss what you were working on yesterday, what you will be working on today and any blockers in your way.
It allows for chances to pivot and change and keep `agile` if necissary

13. What are some advantages **and** disadvantages to using OAuth to authenticate a user?

An advantage is you offload the security concerns to another website/authority this allows you to not worry about securing that as much and allows you to focus more on a better application

Another advantage is that it is a more seamless experience for a user. Many times a user will not sign up for your service if they have to input all of their information that already exists on many other websites.

A disadvantage is that you offload the security concerns to another website/authority, this means that you have to trust them to keep users data safe and that they will not ever give you faulty information.
