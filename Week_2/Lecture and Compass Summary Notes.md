# Week 2 Summary Notes
##  Instructors Notes and/or Videos
* Lec 01: [Notes](https://github.com/DevHalpin/lectures2022/tree/main/flex/14_11_Eve/mod1/w02/objects) and [Video](https://vimeo.com/774068202/da86cc3e9b?embedded=false&source=video_title&owner=147384195)
* Lec 02: [Video](https://vimeo.com/775355309/310b9cab67?embedded=true&source=video_title&owner=147384195)
## Primitive and Objects
* Primitive Types in Javascript
  * undefined
  * null
  * boolean
  * string
  * number
  * symbol
* Primitives are immutable. Everythign that isn't primitive is an object.
* Objects
  * Contain key-value pairs; each key maps to a value
  * Contain keys which are always strings (or symbols, but it's less common and not important right now)
  * Have unique keys; the same key cannot appear twice in an object
  * Have their keys point to values which can be of any type.
  * Object doesn't have a length property
  * Objects have this. keyword to help avoid hard coding
* Anything other than the 6 items above are objects. Primitive cannot be modified, however, objects can. The `for in` loop can be used to iterate through an object.
* `Passing reference` changes the original data. This occurs usually for objects
* `Passing value` creates a new piece of data and the original isn't changed. This occurs usually for primitives 

## Object Oriented Programming vs Function Focused Programming
* Regardless of the type of programming the code shoult always be `DRY` - Don't Repeat Yourself.
* Your code should also always run from top to bottom. Function declaration doesn't follow that rule which is why function expression is recommended more.

## Functions
* `Functions as Objects`: Can be stored in variables and passed around. Can also do everything that other objects can do (like having properties assigned to them). You can modify functions like you can variables. That's why they're called first class objects. You can pass functions are arguments and also return (this is a lot like function composition aka function invocation) them.
* `Single Responsibility Principle` says that a function should always do one thing..
* `Function Declaration` is when the function isn't assigned a variable. The benefit is that `this` can be used.
* `Function Expression` is when the function is assigned a variable. Always try to use this one.
* `Anonymous Functions`: Unamed or unassigned (to a variable) functions
* `Arrow Functions`: Anonymous one liner functions
* `First Class Functions`: An object (function) with no restrictions on its creation, destruction, or usage. This includes the ability to be passed as an argument, returned from a function, and assigned to a variable
* `Callback Functions`: Functions that are a parameter of a function. Functions that take in callbacks are referred to as `Higher Order Functions`
* `Inline Function`: A callback function that is coded inside the parameter of the first class function. A lot of times anonymous functions are used for inline functions. Anonymous arrow functions made them more succinct.
* `Closures`: When a function retains the context of a parent function, we call that a "closure". There is also an alternative approach of an immediately-invoked function expression (IIFE) to achieve a similar result. Although, it has some limitations.

## Vim
* Although, I don't understand that point of this software or what it does the main modes of Vim are edit (pressing `i`) and command (by default or pressing `esc`).
* `H,J,K,L`: `H` moves left; `K` moves up; `L` moves right; `J` moves down.
* `Y` copies a line of text to the buffer.
* `P` pastes it to the cursor's current position.
* `dd` will delete the whole line of text. This will also effectively "cut" a line of text as well. When you delete a line, it's placed in the buffer.
* `yy` copies a whole line of text.
* `w` while in command mode, it saves the file.
* `:wq` - write (save) and quit file (and vim)
* `:q!` - quit and ignore changes made since last file save.

## Problems of this week
* [Lotide](https://github.com/IrhaAli/lotide) (Count Only, CountLetters, LetterPositions, FindKeyByValue, EqualObjects, AssertObjectsEqual, Map, TakeUntil, FindKey)
* [Raisin' Arizona](https://gist.github.com/IrhaAli/373c4bc28228cd5260f75e4e6f7a3646)
* [Sales Tax](https://gist.github.com/IrhaAli/87aca2eb86a5df67c2addcd711b6e898)
* [Social Network Analysis](https://gist.github.com/IrhaAli/7c6cd1c3d41ae4970b6fec9bd68de32c)
* [Sort](https://gist.github.com/IrhaAli/3ff30bb85229842bf0b205c5abccfdab)
* [Closure Problems](https://flex-web.compass.lighthouselabs.ca/workbooks/flex-m01w2/activities/238?journey_step=30&workbook=5) (MakeLoadedDie, CountdownGenerator, WrapLog)