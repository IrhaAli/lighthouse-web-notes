# Week 3 Summary Notes
##  Instructors Notes and/or Videos
* Lec 01: [Notes](https://github.com/DevHalpin/lectures2022/tree/main/flex/14_11_Eve/mod1/w03/TDD_with_Mocha_Chai) and [Video](https://vimeo.com/776449131/e17278b95f)
## Testing
* Use assert library to do in depth testing.
* `To import a function/library:` The file will need to be required via the following syntax const functionName/libraryName = require('filepath').
* `To export a function:` Type module.export = name of function at the bottom of the file with the function. Another way to export a function is by putting export before the function name
* `NPM (Node Package Manager):` Allows us to download packages for us to use like Mocha and Chai for testing.
* `Mocha and Chai:` It is a testing tool for Javascript. Go into the folder where the test file is.
It offers several benefits over manual testing:
  * it saves testing time (by not having to perform manual tests over and over)
  * it saves debugging time (by catching bugs earlier)
  * it makes it easier to program (because we don't need to keep the entire application in our heads, just the part that we're working on... if we break something, our tests will let us know)
  * it makes it easier to come back to a program after some time (programmers forget things, but tests do not)
  * it makes it easier to work together (we wrote some widget and know how it works, but our team-mates probably don't; our tests will catch bugs introduced by others on our team, and vice versa)
  * it acts as documentation (readings tests is a great way to learn about how code is meant to be used)
  * it improves the quality of our code (writing code that is easy to test often requires us to change how our code is structured -- for the better)
* `Unit Testing:` Devide and test software into smaller units. The reason for using unit testing is that the code gets more and more complicated to keep track of all the ways we need to test it.
* A good reason for writing tests is that it allows us to make our code more modular.

## Debugging
### Troubleshooting tips
* pseudo-coded the solution?
* ...googled the error message I am getting?
* ...actually READ the error message?
* ...double-checked my syntax?
* ...linted my code?
* ...pair programmed or gotten a peer to code review?
* ...rubber-ducked the problem?
### Rubber Duck Debugging
* Beg, borrow, steal, buy, fabricate or otherwise obtain a rubber duck.
* Place rubber duck on desk and inform it you are just going to go over some code with it, if that's all right.
* Explain to the duck what your code is supposed to do, and then go into detail and explain your code line by line.
* At some point you will tell the duck what you are doing next and then realise that that is not in fact what you are actually doing. The duck will sit there serenely, happy in the knowledge that it has helped you on your way.

## Function Scope in Javascript
* Arrow functions don't declare their own scope.
* Scope also occurs w.r.t if statements and more

## More about Objects and OOP
* Having functions inside objects is a good idea. The functions are then called methods. It's a place to use `this`. The benefit of doing this is that it emphasizes the functions are only relevant to a certain object.
* Common practice in programming is to group related data and functions together under a single object.
* Arrow Function syntax can vary based on how simple the function is
* Arrow functions don't get assigned a value for this (in the way that traditional function expressions do).
  * This "limitation" is in fact intentional, and can be used as an advantage in certain situations - situations where it is beneficial to inherit the value of this from its lexical scope. Such as the this.firstName being read in the sayHello method.
* OO is a software development paradigm
* OO is a popular way to solve code organization, re-use and modularity
* OO is very important to learn due to its popularity
* JavaScript is not strictly OO in the way that Java or Ruby are
* Functional Programming is an alternative paradigm, and one that JavaScript also encourages
* An object is a little bundle of information, also known as state
* JavaScript's object system is based on another pattern known as prototypes, not classes. Classes were added to Javascript in ES6 and simply help us work with prototypes in an easier way. There was no concept of classes in Javascript before ES6 and yet the community had still been doing OOP in Javascript without this feature. Older JavaScript code is therefore more likely to use prototypes instead of classes.
### Classes and Objects
* Difference between classes and objects is that a class is the blueprint of the house and object is the house, itself. You can create as many houses but you only create one blueprint.
* Classes can be inherited via `extends`.
* Overriding methods in subclasses to change their behaviour. Sometimes this is all you need, but other times we end up repeating some things in the overriding methods. That brings us to point 2 below.
* Using super in the overriding methods in order to avoid repeating code that's already present in the superclass.
* `Getters and Setters:` The concept of getters and setters and how to use the get and set keywords in JavaScript. Setters allow us to validate data before assigning it to a property and getters allow us to compute a value on the fly instead of simply pulling it out of a property. The get and set keywords just make our object's interface more simple.
* OOP Best Practices
  * Abstraction
  * Private vs. Public
  * Single Responsibility Principle
  * Inheritance

## Recursions
* Recursion is a tool you can use as an alternative to traditional iteration using for and while loops.
  * Every recursive function must have a base case and a recursive case.
  * Each recursive call should break down the current problem into a smaller, simpler one.
  * The recursive calls must eventually reach the smallest version of the problem, the base case.
  * The base case is when the problem can be solved without further recursion.

## Problems of this week
* [Lotide](https://github.com/IrhaAli/lotide) (Count Only, CountLetters, LetterPositions, FindKeyByValue, EqualObjects, AssertObjectsEqual, Map, TakeUntil, FindKey)
* [Music Library](https://gist.github.com/IrhaAli/5e70b68181dd0f1d58d54b88db0085e2)
* [Sum From a to b Test](https://github.com/IrhaAli/sum-from-a-to-b-test-js)
* [Sum Array of Numbers](https://gist.github.com/IrhaAli/8a60b42099043a98a2a94888d7858a1f)
* [The Swapper](https://gist.github.com/IrhaAli/9984a77648ce45ee68ac8f9f0a4d96ba)
* [Should I Buy This Car](https://flex-web.compass.lighthouselabs.ca/workbooks/flex-m01w3/activities/286?journey_step=31&workbook=6)
* [Name Formatter](https://gist.github.com/IrhaAli/f83d8288dc6ca76745b838e501f0aaa7)
* [To Do List](https://github.com/IrhaAli/todo-list-js-exercise)
* [Luhn](https://flex-web.compass.lighthouselabs.ca/workbooks/flex-m01w3/activities/266?journey_step=31&workbook=6)
* [Stock Market](https://gist.github.com/IrhaAli/d2ba33a642f6900e3f58e6b1064cd53f)
* [Poppin Bottles](https://gist.github.com/IrhaAli/9ddf662738b61ad6ca7b58b58651ee40)