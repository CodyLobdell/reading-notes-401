>> Readings: Express, NPM, TDD, CI/CD <<
Below you will find some reading material, code samples, and some additional resources that support today’s topic and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

Reading

An introduction to NodeJS and Express

Explain middleware, answer as though I were a non-technical recruiter.
- Middleware is a program that acts as a moderator for two programs communicating back and forth.


Express the most popular Node web framework.


Express is “unopinionated.” What does that mean?
-  Less restrictions on the way things get done or what is used to get it done.


What is a module and why is modularity useful to us as developers?
- Modular programming usually makes your code easier to read because it means separating it into functions that each only deal with one aspect of the overall functionality. It can make your files a lot smaller and easier to understand compared to monolithic code.



What is NPM?

What version of npm are you running on your machine?
- 9.5.1


What command would you type to install a library/package called ‘jshint’ into your node project?
- "npm install jshint"



What is TDD?

Explain why tests are important. Please explain as though I were your non technical elder.
- Tests are important, because they tell us if code is being processed the correct way.


What are three expected benefits of testing
- 


Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests. 
- Forgetting to run tests frequently, writing too many tests at once.
- Partial adoption – only a few developers on the team use TDD
  Poor maintenance of the test suite – most commonly leading to a test suite with a prohibitively long running time

CI/CD

What are three benefits of Continuous Integration?
- Deployment frequency: Automated tests and builds are a prerequisite to automated deploy.
   Time to restore service: Automated pipelines enable fixes to be deployed to production faster, reducing mean time to resolution (MTTR).
   Change failure rate: Early automated testing greatly reduces the number of defects that make their way to production.


What is the difference between Continuous Delivery and Continuous Deployment?
- Continuous Delivery is a software engineering practice where the code changes are prepared to be released. Continuous Deployment aims at         continuously releasing the code changes into the production environment.


Explain how GitHub fits into this process assuming the listener comes from a non-technical background
- GitHub Actions is a continuous integration and continuous delivery (CI/CD) platform that allows you to automate your build, test, and deployment pipeline.
Bookmark and Review

nodeJS docs

npm docs

express docs

http status codes

supertest

Reflection
What are your learning goals after reading and reviewing the class README?
- I want to be able to fully understand how to incorporate Express Middleware for future projects.