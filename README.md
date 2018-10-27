
# JS questions for interviews

Here i collected several JS questions that I could be used during a job interview
and also as a tool to learn new stuff. I think questions are well balanced
between JS implementation details and general, broad topics.


> ### Could you explain Coercion in JS?


> ### Could you explain Scope in JS?


> ### Could you explain equality in JS?


> ### Could you explain what a callback function is? Could you provide a simple example?


> ### What does “use strict” do?


> ### What are the similarities and differences between Null and Undefined in JS?


> ### How would you write a function that allows you to do this?

```js
  var addSix = createBase(6)
  addSix(10) // returns 16
  addSix(21) // returns 27
```


> ### Explain Values and Types in JavaScript


> ### What is event bubbling? How may you prevent it?


> ### What is let keyword in JavaScript?


> ### How would you check if a number is an integer?


> ### What is IIFEs (Immediately Invoked Function Expressions)?


> ### How would you compare two objects in JavaScript?


> ### Could you explain the main differences between ES5 and ES6?


> ### Explain the difference between “undefined” and “not defined” in JS


> ### What is the difference between anonymous and named functions?


> ### What is “closure” in JS? Could you provide an example?


> ### What are some of the features introduced in version ES2015 of EcmaScript? And beyond that?


> ### Explain the Prototype Inheritance in JavaScript


> ### Create a function that checks if a given string is isomorphic

*Two strings (**s** and **t**) are isomorphic if the characters in **s** can be replaced to get **t**.*

```
  // Example 1:
  Input: s = "egg", t = "pdd"
  Output: true

  // Example 2:
  Input: s = "foo", t = "bar"
  Output: false

  // Example 3:
  Input: s = "paper", t = "title"
  Output: true
```

> ### What does the term “transpiling” mean?


> ### How does the `this` keyword work? Provide some examples.


> ### How would you make the following snippet work?

```js
  var arr = [1, 2, 3, 4, 5]
  var avg = arr.average()
  console.log(avg) // => 3
```

> ### What is Hoisting in JS? What benefits it gives?


> ### Can you name two programming paradigms important for JavaScript developers?


> ### JavaScript does not implement the concept of “private” variables. How would you achieve a similar behavior?


> ### What’s the output of the following code snippet? Why?

```js
  var x = 1

  function foo() {
    console.log('x is:', x)
    var x = 2
  }

  foo()
```


> ### What’s the return value of each function in the following snippet? 

```js
  console.log(c())
  console.log(b())
  console.log(a())

  var a = function() { return 'a' }
  var b = () => 'b'
  function c() { return 'c' }
```


> ### What’s the output of the following code snippet? Why?

```js
  [1, 2, 3].map(parseInt)
```


> ### Regarding last question: How would you achieve the expected output?


> ### What’s the output of the following code snippet? Why?

```js
  var a = 1

  function b () { 
    a = 10; 
    return; 
    function a() {} 
  }

  b()
  console.log(a)
```


> ### What’s the output of the following code? Why? 

```js
  const arr = [1, 2, 3, 4]

  for (var i = 0; i < arr.length; i++) {
    setTimeout(function() {
      console.log(arr[i])
    }, 1000)
  }
```

> ### How would you modify the last question to output numbers from 1 to 4, without removing the for loop? Provide at least two examples


> ### What is functional programming? What are its pros and cons vs object-oriented programming?


> ### What are two-way data binding and one-way data flow, and how are they different?


> ### How would you select all H1 and H2 from a page, and log their content to the console?


> ### What are the differences between `Array.prototype.map` and `Array.prototype.reduce`?


> ### Is JS a render-blocking or non-render-blocking resource? How would you achieve the opposite behavior?


> ### What’s the difference between the following code snippets? When should I use one or another?

```js
  // 1
  var func() {...}
  module.exports = func

  // 2
  var func() {...}
  export default func
```


> ### Name at least one feature from another programming language that you’d like to see ported to JavaScript


> ### How would you assert that a function is working properly, without the aid of a testing library?


> ### Is the following syntax valid? Explain it

```js
  var [ a = 1, a = 2 ] = foo()
```


> ### How would you achieve the following output?

```js
  foo.bar === foo.bar  // false
```

> ### Write a function `f()` that works in the following scenarios:

```js
f(2, 3)  // 8
f(2)(3)  // 8

var g = f(3)
g(2)  // 9
```

> ### How would you define a pure function? Can you write some example of a pure and impure functions?