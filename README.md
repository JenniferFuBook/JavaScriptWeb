# JavaScript Web
As a veteran software engineer, I have architected and developed a number of software management systems using Java/JavaScript. I have been the interviewer and interviewee for many frontend developer positions. I published [ACE Your Java Interview](https://www.amazon.com/ACE-Your-Java-Interview-Jennifer/dp/1484104935/ref=tmm_pap_swatch_0?_encoding=UTF8&qid=1566344263&sr=1-9) a few years ago, which is still a best-seller today.

My fellow developers ask me when I am going to publish an interview reference book for JavaScript. I have been working on it for a while. The content keeps changing along with the evolving ECMAScript standards, as well as emerging frameworks and libraries. It becomes a never-ending project.

For years, I have been nourished by a lot of open source materials. I have read many articles, and some of them become my favorites. Why don’t I link them in a centralized location to make a JavaScript Web for easy access? It is no longer a conventional book. It is composed by many people’s work, and it is a resource for frontend job interview and daily development work.

This provides a number of advantages: 

*	It allows constantly adding and updating content.
*	It speeds up the writing process.
*	It gets on-going feedback. 

Happy reading and practicing!


## Types and Type Coercion 
JavaScript has 2 data types: primitives and objects.
There are 7 primitive data types: string, number, bigint, boolean, null, undefined, and [symbol](https://hacks.mozilla.org/2015/06/es6-in-depth-symbols/).

[Type coercion](https://medium.freecodecamp.org/js-type-coercion-explained-27ba3d9a2839) is the process of converting value from one type to another. An object is converted to a primitive, which is then converted to the final type. Type coercion will transform a value to string, boolean, or number. Values can be converted explicitly, or implicitly by operations between different types or by the surrounding context. 

The strict equality (===) doesn’t trigger type coercion, while the loose equality operator (==) does type coercion if needed, and then compares.

## Functional Programming
[Functional programming](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-functional-programming-7f218c68b3a0) is a programming paradigm. It builds software by composing pure functions, avoiding shared state, mutable data, and side effects. Functional programming is declarative rather than imperative, and application state flows through pure functions.

[Higher-order functions](https://dev.to/damcosset/higher-order-functions-in-javascript-4j8b) are functions that take other functions as arguments or return functions as their results. Functions are objects in JavaScript. It is treated as first-class citizens.

[Currying](https://codeburst.io/perpetual-currying-in-javascript-5ae1c749adc5) is about decomposing a function taking multiple arguments into numerous functions with single arguments.
It is named after [Haskell Curry](https://en.wikipedia.org/wiki/Haskell_Curry).

[Microservices](https://medium.engineering/microservice-architecture-at-medium-9c33805eb74f) are not specific to JavaScript. However, conceptually, functional programming is an analogy for microservices: single purpose, loose coupling, and high cohesion. It is fun to read about this hot topic.

## Regular Expressions
Regular expressions are patterns used to match character combinations in strings. It is extremely effective for searching, manipulating, and validating strings.

[A Practical Guide to Regular Expressions](https://blog.bitsrc.io/a-beginners-guide-to-regular-expressions-regex-in-javascript-9c58feb27eb4) is comprehensive with handson examples.

[Lookbehind and Lookahead](https://itnext.io/whats-new-in-javascript-google-i-o-2019-summary-d16bd2308412) are the latest additions to the Regular expression family.
 
[Online Regular Expression Tester and Debugger](https://regex101.com/) is a convenient tool to test out specific regular expressions.

## Linter
A linter is a static code analysis tool for identifying problematic patterns found in JavaScript code. 

* [JSLint](https://github.com/douglascrockford/JSLint): It is the oldest linter. [Douglas Crockford](https://en.wikipedia.org/wiki/Douglas_Crockford) created it in 2002 to enforce the good parts of JavaScript. It is configured and ready to go, and it is not configurable or extensible.

* [JSHint](https://github.com/jshint/jshint): It is a more configurable version of JSLint. It supports many libraries out of the box, such jQuery, QUnit, NodeJS, Mocha, etc. It has basic ES6 support. However, it has no custom rule support.

* [ESLint](https://github.com/eslint/eslint): It is the most popular linter. It is easily extensible, and comes with a large number of custom rules. It has the best ES6 support.

* [TSLint](https://github.com/palantir/tslint): It is a linter to identify and report errors and enforce conventions  for TypeScript. It has been deprecated. The recommended way is using ESLint’s TypeScript support, typescript-eslint. 


* [Html-linter](https://github.com/chinchiheather/html-linter): It is a linter to identify and report errors and enforce conventions for HTML files.

* [Stylelint](https://github.com/stylelint/stylelint): It is a linter to identify and report errors and enforce conventions for styles.

## Testing
### Testing Types

* Unit test: Specify and test one point of the contract of single method of a class. This should have a very narrow and well defined scope. Complex dependencies and interactions to the outside world are stubbed or mocked.

* Integration test: Test the correct inter-operation of multiple subsystems. There is whole spectrum there, from testing integration between two classes, to testing integration with the production environment.

* Acceptance test: Test that a feature or use case is correctly implemented. It is similar to an integration test, but with a focus on the use case to provide rather than on the components involved.

* Functional test: Test features on the business requirements of the system.

* Smoke test: Initial tests to decide whether the system is good enough for continuous testing.

* Regression test: A test that was written when a bug was fixed. It ensures that this specific bug will not occur again.

* System test: Test the software as a black box.

* End-to-end test: Test a user behavior with the system in a complete application environment. 

* Performance test: Test to check the behaviors of the system when it is under significant load. 

### Testing Tools

* Test launchers: Launch tests in a browser or Node.js with user config using the CLI or UI. This can also be achieved by opening the browser manually - Karma, Jasmine, Jest, TestCafe, Cypress

* Testing structure providers: Help arranging test files - Mocha, Jasmine, Jest, Cucumber, TestCafe, Cypress

* Assertion functions: Verify whether the results a test returns are as expected - Chai, Jasmine, Jest, Unexpected, TestCafe, Cypress

* Generate and display test progress and results - Mocha, Jasmine, Jest, Karma, TestCafe, Cypress

* Mocks, spies, and stubs - Isolate certain parts of tests and catch their side effects - Sinon, Jasmine, enzyme, Jest, testdouble

* Generate and compare snapshots of component and data structures: Make sure changes from previous runs are intended - Jest, Ava

* Generate code coverage reports: Verify how much of the code is covered by the tests - Istanbul, Jest, Blanket

* Browser controllers: Simulate user actions for Functional Tests - Nightwatch, Nightmare, Phantom, Puppeteer, TestCafe, Cypress

* Visual regression tools: Compare the site to its previous versions visually by using image comparison techniques - Applitools, Percy, Wraith, WebdriverCSS

## Gists
Gists are a collection of code snippets for understanding the JavaScript concepts. It is also a resource to review before a frontend job interview.

[curry](https://gist.github.com/JenniferFuBook/b4e0d9a4bf2c2ce2da930208525e0cca), [debounce](https://gist.github.com/JenniferFuBook/dce897550feef47e13dbc2c75e059733), [mergeDeep](https://gist.github.com/JenniferFuBook/26afd67cc269e48aad28fff40176e698), [throttle](https://gist.github.com/JenniferFuBook/61697bb9b7917af7cecdcb4461b45074)
