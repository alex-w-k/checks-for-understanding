## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's the most useful thing you learned from completing the intermission week work?
- How to javascript in general
2. What are some tools to help debug JavaScript code?
- debugger/chrome devtools
3. What are some tools you need in order to unit test your JavaScript?
- mocha/chai
4. What is the syntax for invoking a function?
- functionName()
5. What is CORS?
- Cross-Origin Resource Sharing -- basically securing cross domain resource sharing and blocking the API calls unless specifically allowed
6. How do we enable CORS?
- CORS is enabled by default in modern browsers
7. What's `this` in JavaScript?
- this refers to the function that is currently being processed.
8. What is Webpack and why is it useful?
- webpack combines all js files into one single file and can translate it from other ECMAScript versions and/or minify uglify it to be better processed by browsers.
9. When/why do you want to use event delegation?
- You use event delegation to allow something to be accessed with JS after pageload.
10. What is a callback function?
- a callback function is a fucntion that is called after another function is done processing. Like passing a function to another function.
11. What's `npm` and what do we use it for?
- node package manager and it is used to install dependancies for JS, like bundler for JS.

#### Review  
12. What's the MVC design pattern? Describe each part of MVC.
- Model/View/Controller -- Models are the objects that typically refer to items in a database, Views are the individual pages that the user will see, Controllers decide where to route requests and can hold instance variables.
13. What are a few ways to optimize a Rails application?
- Reducing page weight, reducing long DB calls by using faster calls and/or adding more opimized indexes.
14. What's a background worker? When would we want to use a background worker?
- a background worker will do a process in the backgound and can be helpful if you have a longer process like processing and optimizing images but you want the next page to load.
