# Week 1 Summary Notes
## How to Approach a Problem
* Step 1: Fully understand the problem
* Step 2: Start with pseudocode as a way to break down the problem
* Step 3: Translate the solution to Javascript
* Step 4: Test the code to see it work
* Step 5: See if the code can be more succinct (get feedback)
* Step 6: See if it can be more efficient (get feedback)

## Function Best Practices
1.  Give your functions precise verb/action based names
2.  Use `camelCasedNames` (like this one)
3.  Properly indent the function code
4.  Functions should focus on a single task: returning a value or causing a side effect. _Break your function into additional smaller functions if you find it doing two or more things_
    *   One single task could be to compute and return a value (eg: `zeroPad`)
    *   Another single task could be to perform a side effect such as logging a message to the screen (eg: `printFarmInventory`)
5.  It is ideal if functions try to avoid reading outer scope variables. If a function needs some information / data, then that data should instead be passed in as a parameter, making it available within the function's _inner scope_.

## Variable Scope in Javascript
* `Block (Local) Scope Variables`: wrong block scope variable will lead to many variable declaration of the same variable (ie redundancy)
* `Global Scope Variables`: Too many will fill up the global namespace storage


## Error Messages
* [How to understand/fix/approach an error message](https://flex-web.compass.lighthouselabs.ca/workbooks/flex-m01w1/activities/177?journey_step=29&workbook=4)

## Coercion and Truthy/Falsey
* The === checks if the two values on each side are equal whereas the == coerces one to the other type then compares them. For more information read [this](https://flex-web.compass.lighthouselabs.ca/workbooks/flex-m01w1/activities/180?journey_step=29&workbook=4).

## Problems of this week
* [Lotide](https://github.com/IrhaAli/lotide) (AssertEqual, Head, Tail, EqArrays, AssertArraysEqual, WIthout, Flatten, Middle)
* [What's for lunch](https://gist.github.com/IrhaAli/fbb13fa06907a717ecf6515be8002f44)
* [Adding Numbers](https://gist.github.com/IrhaAli/a58011d560fd3a8ab293e221a0972a8d)
* [Reverse a String](https://gist.github.com/IrhaAli/d2fb6316353f21fe22a9f8a78281ac6f)
* [Pig Latin Translator](https://gist.github.com/IrhaAli/e433251043f21a077abfd77c5a8b449a)
* [Minimum Values](https://flex-web.compass.lighthouselabs.ca/workbooks/flex-m01w1/activities/170?journey_step=29&workbook=4)
* [Joining Concepts](https://flex-web.compass.lighthouselabs.ca/workbooks/flex-m01w1/activities/173?journey_step=29&workbook=4)
* [Rolling Dice](https://gist.github.com/IrhaAli/0d3bb166c8dc4aa0124a15836dee300f)
* [Password Obfuscator](https://gist.github.com/IrhaAli/c4bdb0e05a6b551b2e96e30ce65b55b0)
* [Palindrome](https://gist.github.com/IrhaAli/0336a372255a6922a3ac90af5fab36d5)
* [Print In Frame](https://gist.github.com/IrhaAli/11877dbe7c500f47dc5ac99304892554)
* [Calculate Day in Year](https://flex-web.compass.lighthouselabs.ca/workbooks/flex-m01w1/activities/189?journey_step=29&workbook=4)
