## Week Three - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. At a high level, what is Node?

Node is a JS runtime that enables javascript to be run outside of the browser.

2. What is Express? What is Express similar to in the Ruby world?

Express is a light Javascript framework for backend web applications. It is similar to Sinatra in the ruby world.


3. How do we setup a route when creating an API with Node and Express? Please provide a code snippet.

```js
app.get('endpoint', function(request, response) {
  response.json(data)
})
```

4. What do we use Knex for?

We use KNEX to interface with a databse using node.


5. How could you organize your code to follow the MVC design pattern in your Quantified Self project?

The server.js file could be like the routes file and then you could set up a folder structure like this:
```
lib/
├── controllers
|    ├── food_controller.js
|    └── meal_controller.js
└── models
    ├── food.js
    └── meal.js
```

and then use the controllers and models just like rails.

6. How do you execute raw SQL in node?

`database.raw('query')`

7. What are some advantages to having your front end and back end code live in separate applications? What are some disadvantages?

An advantage is that you can use different frameworks for the front end and for the back end.

A disadvantage is that you now have two seperate code bases to manage

#### Review  

8. Describe DNS.

DNS is how your browser know what web address belongs to what IP address. 


9. What does writing clean code mean to you?

Clean code is writing code that is easily modifiable and and upgradable. 
It is also writing code that is easily understood by anyone coming into the code base to understand what is happening. 
Using DRY to make nice short functions/methods.

10. If you were building an application that models hotels, what classes would you need? What classes would be responsible for what functionality?

Building: number of rooms, number of staff, what ammenities are available, address, phonenumber, etc
Room: how many beds, smoking/non-smoking?, size of beds, location, room number, price, etc
Staff: role, hours, wage, name, etc

