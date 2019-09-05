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

## Gists
Gists are a collection of code snippets for understanding the JavaScript concepts. It is also a great resource to review before a frontend job interview.

[Curry](https://gist.github.com/JenniferFuBook/b4e0d9a4bf2c2ce2da930208525e0cca)
