# Express, NPM, TDD, CI/CD

## An Introduction to NodeJS and Express
1. Explain middleware, answer as though I were a non-technical recruiter.
  - Middleware is code that handles a request or response between the client sending the request and receiving a response. A common piece of middleware is a logger to see what requests are coming in to the server. Another example could be middleware for authentication. The middleware might check if you have the right username and password before actually sending the request to the server.

2. Express the most popular __ __ ____.
  - Framework

3. Express is “unopinionated.” What does that mean?
  - This means tat you can insert any type of middleware into the request handling chain. Express doesn't care what the middleware is and you can structure the middleware anyway you like.

4. What is a module and why is modularity useful to us as developers?
  - A module is a reusable piece of code. This can mean a lot less work. I think Express is a great example of this because with express I can setup a basic REST API server in a few hours, but if I had to write out all that code every time it would take much longer. It is also unnecessary since the framework of the server never changes, the only thing that changes is how we want to handle and respond to requests.

## What is NPM
1. What version of npm are you running on your machine?
  - 8.19.1

2. What command would you type to install a library/package called ‘jshint’ into your node project?
  - npm i jshint

## What is TDD
1. Explain why tests are important. Please explain as though I were your non technical elder.
  - Tests are important because if you do it often, you know which piece of code broke your application much faster. If you write a bunch of code, and then try to test it, any of the features could be the issue and you have to map through you code to find out why. If you get a basic application running, and then test after features are added, you know exactly which feature is the issue if the test fails.

2. What are three expected benefits of testing
  - reductions in defect rates
  - overhead of continuous testing is offset by reduction in effort during a projects final phases
  - improved design qualities

3. Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.
  - Individual
    - forgetting to rung tests frequently
    - writing over trivial test or tests for trivial code
  - Team
    - only part of the team uses TDD
    - poor maintenance of the test suite

## CI/CD
1. What are three benefits of Continuous Integration?
  - ensure everyone's changes work together
  - catch bugs
  - reduce merge conflicts

2. What is the difference between Continuos Delivery and Continuous Deployment?
  - Continuous Delivery - practice of developing software in a way that you could release it at any time
  - Continuous Deployment - process that allows you to deploy new features into production with little or no downtime

3. Explain how GitHub fits into this process assuming the listener comes from a non-technical background
  - Github runs CI tests every time someone want to integrate changes into the main branch

## Things I want to learn more about

### Links
[An introduction to NodeJS and Express](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)

[What is NPM?](https://docs.npmjs.com/about-npm)

[What is TDD?](https://www.agilealliance.org/glossary/tdd/#q=~(infinite~false~filters~(postType~(~'page~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'tdd))~searchTerm~'~sort~false~sortDirection~'asc~page~1))

[CI/CD](https://www.youtube.com/watch?v=xSv_m3KhUO8)

[nodeJS docs](https://nodejs.org/en/docs/)

[npm docs](https://docs.npmjs.com/)

[express docs](https://expressjs.com/en/4x/api.html)

[http status codes](https://www.restapitutorial.com/httpstatuscodes.html)

[supertest](https://github.com/visionmedia/supertest)