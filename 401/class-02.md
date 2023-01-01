<img src="https://members-csforall.imgix.net/members/logos/code-fellows-logo-horizontal-2-color-black.png" width="340" height="66">  

# Code 401 Reading Notes

## Class 02 Reading Notes

### An Introduction to NodeJS and Express

```
1. Explain middleware, answer as though I were a non-technical recruiter.
   - Middleware refers to software that acts as a bridge between different applications, enabling them to communicate and exchange data. In the context of web development, middleware is often used to handle tasks such as routing, parsing requests, and handling errors in an Express application.
2. Express is the most popular __ __ ____.
   - Express is the most popular Node.js web application framework.
3. Express is “unopinionated.” What does that mean?
   - When something is "unopinionated," it means that it does not make assumptions or impose specific ways of doing things. In the context of Express, this means that the framework does not dictate how you should structure or build your web application, allowing you to have more flexibility and control.
4. What is a module and why is modularity useful to us as developers?
   - A module is a self-contained piece of code that performs a specific task or function. Modularity is useful because it allows developers to divide their code into smaller, more manageable units that can be easily reused or combined with other code to create larger applications.
```

### What is NPM?

```
1. What version of npm are you running on your machine?
   - To check the version of npm that is currently installed on your machine, you can type `npm -v` in the command line.
   - npm version 8.19.2
2. What command would you type to install a library/package called ‘jshint’ into your node project?
   - To install the 'jshint' library/package into a Node project, you can type `npm install jshint` or `npm i jshint` in the command line.

```

### What is TDD?

```
1. Explain why tests are important. Please explain as though I were your non technical elder.
   - Tests are important because they help ensure that a piece of software is working as intended, and can help identify and fix any issues or bugs before the software is released. For a non-technical elder, you could explain it as a way to make sure that a program is functioning properly and doing what it is supposed to do.
2. What are three expected benefits of testing
   - Some benefits of testing include: improved software quality, increased confidence in the code, and easier maintenance and updates.
3. Name at least 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.
   - Some individual pitfalls commonly encountered while writing tests include: writing tests that are too specific or brittle (i.e. prone to breaking when the code changes), and not writing enough tests to adequately cover all scenarios. Some team pitfalls include: not having a clear testing strategy or process, and not having a culture of testing within the team.

```

### CI/CD

```
1. What are three benefits of Continuous Integration?
   - Some benefits of Continuous Integration (CI) include: faster identification and resolution of issues, earlier detection of problems, and better collaboration between team members.
2. What is the difference between Continuos Delivery and Continuous Deployment?
   - Continuous Delivery (CD) refers to the practice of automatically building, testing, and releasing software updates in a way that makes them ready for deployment at any time. Continuous Deployment takes this one step further by automatically deploying the software updates to production as soon as they pass the required testing and approvals.
3. Explain how GitHub fits into this process assuming the listener comes from a non-technical background.
   - GitHub is a version control and collaboration platform for developers. In the context of CI/CD, GitHub can be used to store and manage the codebase for a project, and to set up automated workflows that trigger builds, tests, and deployments whenever code changes are pushed to the repository. This allows teams to continuously integrate, test, and deploy their code, without having to manually perform these tasks.

```